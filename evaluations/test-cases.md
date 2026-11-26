# AI Prompt Library – Test Cases

These test cases are used to evaluate the ten AI prompts developed for HarbourView Hotel. Each scenario represents a realistic hotel operation or guest service situation.

## Test Case 1 – P01: Booking Enquiry Classification

A guest emails HarbourView Hotel asking whether a room is available for two adults for three nights in December. The guest also asks whether breakfast is included.

**Purpose:** Test whether AI identifies the main enquiry, additional questions, missing information and appropriate department.

## Test Case 2 – P02: Booking Response Preparation

A guest asks about booking a room for two adults. The reservations team has verified that the room costs $220 per night and breakfast is available for an additional $25 per person per day.

**Purpose:** Test whether AI prepares a professional response using only the supplied and verified information.

## Test Case 3 – P03: Pre-Arrival Guest Summary

A guest has a confirmed booking for two nights. The guest has requested a king-size bed and early check-in. Early check-in has not yet been approved.

**Purpose:** Test whether AI prepares a useful pre-arrival summary and distinguishes confirmed details from unconfirmed requests.

## Test Case 4 – P04: Guest Request Classification and Routing

A guest contacts reception at 10:00 pm reporting that the air conditioning in their room is not working.

**Purpose:** Test whether AI identifies the responsible department, urgency and appropriate next action.

## Test Case 5 – P05: Housekeeping Prioritisation

Housekeeping has three rooms to clean:
- Room 201: Guest has checked out. A new guest is arriving at 2:00 pm.
- Room 305: Current guest has requested additional towels.
- Room 410: A new guest is arriving at 11:00 am, and the room has not been cleaned.

**Purpose:** Test whether AI prioritises housekeeping tasks using arrival times and guest requirements.

## Test Case 6 – P06: Maintenance Classification

A guest reports water leaking from the ceiling in their bathroom. Water is continuing to drip onto the floor.

**Purpose:** Test whether AI recognises a potentially serious maintenance issue and recommends appropriate escalation.

## Test Case 7 – P07: Restaurant Enquiry

A guest asks whether the hotel restaurant serves vegetarian meals and what time dinner service finishes. The approved restaurant information confirms vegetarian options are available and dinner service finishes at 9:30 pm.

**Purpose:** Test whether AI prepares an accurate and professional response using supplied restaurant information.

## Test Case 8 – P08: Dietary and Allergen Check

A guest informs the restaurant that they have a peanut allergy and asks whether a particular dessert is safe to eat. The supplied menu does not include complete ingredient or cross-contact information.

**Purpose:** Test whether AI identifies missing allergen information and refers the matter to authorised kitchen staff rather than declaring the dessert safe.

## Test Case 9 – P09: Complaint Classification and Escalation

A guest complains that their room was not cleaned during their stay and that they had to contact reception twice. The guest is unhappy and requests compensation.

**Purpose:** Test whether AI classifies the complaint, recommends escalation and prepares an appropriate acknowledgement without promising compensation.

## Test Case 10 – P10: Daily Management Summary

The hotel manager provides the following daily information:
- Occupancy: 85%
- Three rooms are awaiting housekeeping inspection.
- Two maintenance requests remain unresolved.
- Four guest complaints were received.
- The restaurant reported a busy dinner service.

**Purpose:** Test whether AI prepares a management summary, identifies outstanding tasks and avoids inventing information.

---

## Testing Notes

- Each test case should be entered into its corresponding prompt.
- Record the complete AI output in `test-results.md`.
- Evaluate accuracy, clarity, relevance and compliance with the prompt instructions.
- Improve prompts when weaknesses are identified.
- Retest revised prompts and record the results.