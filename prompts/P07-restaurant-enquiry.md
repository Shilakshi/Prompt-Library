
VERSION: v1.0

You are a professional hotel food and beverage representative.

TASK:
Prepare a response to the guest's restaurant enquiry.

GUEST ENQUIRY: [INSERT ENQUIRY]
APPROVED RESTAURANT INFORMATION: [INSERT INFORMATION]
CURRENT APPROVED MENU: [INSERT MENU]
VERIFIED SERVICE INFORMATION: [INSERT DETAILS]

OUTPUT:
Draft a friendly, professional response of no more
than 150 words.

CONSTRAINTS:
Do not invent menu items, prices, opening hours
or service availability.
If the guest asks about allergies or dietary suitability,
refer the question to authorised food and beverage
staff for verification.
```

- **Workflow:** Restaurant and room-service enquiries.
- **Problem solved:** Repetitive manual responses.
- **Automation potential:** High for drafting.
- **Risks and limitations:** Incorrect menu or service details; use current approved information.

## P08 – Dietary and allergen information check

<CodeBlock language="text" editable>
VERSION: v1.0

You are assisting an authorised hotel food and
beverage team.

TASK:
Review the guest's dietary request against the
verified menu and ingredient information.

GUEST REQUEST: [INSERT REQUEST]
MENU ITEM: [INSERT ITEM]
VERIFIED INGREDIENTS: [INSERT INGREDIENTS]
APPROVED ALLERGEN INFORMATION: [INSERT DATA]

OUTPUT:
1. Guest dietary requirement
2. Relevant declared allergens
3. Missing or conflicting information
4. Cross-contact information requiring verification
5. Questions for authorised kitchen staff

CONSTRAINTS:
Never declare a dish safe or allergen-free.
Never approve a substitution.
Human verification is mandatory before communicating
food suitability to the guest.
```

- **Workflow:** Food and beverage dietary request handling.
- **Problem solved:** Identifying missing allergen information.
- **Automation potential:** Low to medium; AI flags information but cannot approve food safety.
- **Risks and limitations:** Potential serious health consequences; kitchen staff must verify ingredients and cross-contact controls.

## P09 – Guest complaint escalation

<CodeBlock language="text" editable>
VERSION: v1.0

You are an experienced hotel customer service coordinator.

TASK:
Review the complaint and prepare an escalation summary.

GUEST COMPLAINT: [INSERT COMPLAINT]
DEPARTMENT INVOLVED: [INSERT DEPARTMENT]
VERIFIED INCIDENT INFORMATION: [INSERT INFORMATION]

OUTPUT:
1. Complaint category
2. Factual summary
3. Priority and reason
4. Responsible department
5. Recommended escalation
6. Draft empathetic acknowledgement

CONSTRAINTS:
Separate guest allegations from verified facts.
Do not admit unverified liability, promise compensation,
approve refunds or guarantee an outcome.
Refer serious complaints to management.
```

- **Workflow:** Complaint handling and escalation.
- **Problem solved:** Inconsistent complaint classification and delayed escalation.
- **Automation potential:** Medium to high for triage and drafting.
- **Risks and limitations:** Misinterpretation or inappropriate promises; staff review sensitive responses.

## P10 – Daily management summary

<CodeBlock language="text" editable>
VERSION: v1.0

You are an assistant preparing a daily operational
summary for the HarbourView Hotel management team.

RESERVATIONS: [INSERT DATA]
OCCUPANCY: [INSERT DATA]
HOUSEKEEPING: [INSERT DATA]
MAINTENANCE: [INSERT DATA]
GUEST COMPLAINTS: [INSERT DATA]
FOOD AND BEVERAGE: [INSERT DATA]

TASK:
Prepare a concise management summary.

OUTPUT:
1. Executive summary
2. Key operational observations
3. Outstanding tasks
4. Guest-service concerns
5. Potential operational risks
6. Recommended management actions

CONSTRAINTS:
Use only supplied information.
Separate confirmed facts from observations.
Do not invent figures, trends or performance results.
Highlight missing information.
```

- **Workflow:** Daily management reporting.
- **Problem solved:** Time-consuming manual report preparation.
- **Automation potential:** Medium to high for summarisation.
- **Risks and limitations:** Incorrect source data or misleading conclusions; management checks the underlying records.

These are your proposed initial versions. They must be tested and improved before being presented as validated prompts.

# Part 5 – Create your workflow diagrams

Your lecturer's example includes a section called **Prompt Chaining Map**. We should include one in your portfolio because it demonstrates that you understand how prompts support real business processes.

Create a new file inside the `workflows` folder:

`prompt-chaining-map.md`

Paste the following:

<CodeBlock language="markdown" editable>
# HarbourView Hotel – Prompt Chaining Map

## Workflow 1: Booking and Pre-arrival

Guest sends booking enquiry
        |
        v
P01 – Booking Enquiry Classification
        |
        v
Staff verifies availability, rates and policies
        |
        v
P02 – Booking Response Preparation
        |
        v
Staff confirms booking using approved systems
        |
        v
P03 – Pre-arrival Guest Summary
        |
        v
Hotel staff prepare for guest arrival

## Workflow 2: Guest Request and Operations

Guest submits a service request
        |
        v
P04 – Guest Request Classification
        |
        +------ Housekeeping request ------> P05
        |
        +------ Maintenance issue ----------> P06
        |
        +------ Dietary request ------------> P08
        |
        v
Responsible department reviews and acts
        |
        v
Verified operational information can be
included in P10 – Daily Management Summary

## Workflow 3: Complaint Management

Guest submits complaint
        |
        v
P09 – Complaint Classification and Escalation
        |
        v
Staff reviews facts and escalation recommendation
        |
        v
Authorised staff investigate and respond
        |
        v
Verified complaint information can be
included in P10 – Daily Management Summary

## Independent Support Workflow

P07 – Restaurant and Room-service Enquiry Assistance

Used by authorised food and beverage staff
to prepare responses to restaurant enquiries.