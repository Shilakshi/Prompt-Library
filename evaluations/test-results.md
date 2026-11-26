# HarbourView Hotel – AI Prompt Testing Results

## P01 – Booking Enquiry Classification

**AI tool used:** ChatGPT

**Prompt version tested:** v1.0

**Test scenario:** A guest asks whether a room is available for two adults for three nights in December and whether breakfast is included.

**Actual AI output summary:**
The AI correctly classified the enquiry as a room availability enquiry. It identified breakfast inclusion as an additional question, assigned low urgency, and recommended the Reservations Department. It identified the missing dates and recommended checking room availability, room rates and breakfast arrangements. It also generated an example guest email.

**Evaluation:**
- Accuracy: Correctly classified the enquiry.
- Relevance: Addressed the guest's questions.
- Clarity: The response was generally clear, but the verification table was poorly formatted.
- Safety: Did not invent room availability, prices or breakfast inclusions.
- Limitation: Generated an additional email draft that was not requested in this classification task.

**Improvement required:**
- Improve the formatting of the verification information.
- Instruct the AI not to generate an email draft unless requested.

**Overall result:** Successful initial test. Minor improvements identified.

**Evidence:** Original AI response retained in the ChatGPT conversation. Screenshot to be saved if required.

---

## P02–P10 Testing

Pending testing. Actual outputs and evaluations will be added after each prompt is tested.

## Overall Testing Reflection

To be completed after all ten prompts have been tested.

## P01 – Actual AI Output (Version 1.0)
HarbourView Hotel – Guest Enquiry Classification
Processed – Version 1.0
1. Main enquiry category
Room availability enquiry / Accommodation reservation enquiry

The guest wants to know whether HarbourView Hotel has a room available for two adults for a three-night stay in December.
2. All additional questions
- Is breakfast included in the room rate?
- What accommodation options are available for the requested dates? (Subject to availability verification.)
3. Urgency
Low

This is a general booking enquiry. No immediate urgency, emergency or specific deadline has been mentioned.
4. Recommended department
Reservations Department

The Reservations Department should handle the accommodation availability enquiry and verify the breakfast arrangements.
5. Recommended staff action
1. Acknowledge receipt of the guest's email.
2. Request the exact check-in and check-out dates, as the guest has only specified December.
3. Confirm the number of guests (two adults).
4. Check the hotel's reservation system for room availability for the requested three-night stay.
5. Verify the available room types and applicable rates.
6. Check whether breakfast is included in the room rate or available at an additional cost.
7. Provide the guest with accurate information about available options.
8. Ask whether the guest would like to proceed with a reservation once the details have been confirmed.
6. Information requiring verification
Information	Verification required
Stay dates	Exact check-in and check-out dates
Number of guests	Two adults
Length of stay	Three consecutive nights
Room availability	Check the reservation system
Room types	Confirm available room categories
Room rates	Verify current rates
Breakfast inclusion	Confirm whether breakfast is included
Breakfast pricing	Verify additional charges, if applicable
Reservation status	No booking has been confirmed

Final classification summary
Guest request: Accommodation availability and breakfast information.

Main category: Room availability enquiry

Additional category: Breakfast inclusion enquiry

Urgency: Low


Responsible department: Reservations

Next action: Obtain exact December dates and verify availability, room rates and breakfast inclusions before responding.

Important: No room availability, price, breakfast inclusion or reservation confirmation should be communicated until verified by the Reservations Department.

Example of how the hotel could respond to the guest
Dear Guest,

Thank you for considering HarbourView Hotel for your upcoming stay.

We would be delighted to assist you with your accommodation enquiry for two adults for three nights in December.

Could you please confirm your preferred check-in and check-out dates so that we can check room availability and provide you with the applicable room rates?

We will also confirm whether breakfast is included in the room rate or available at an additional charge.

We look forward to hearing from you.

Kind regards,
Reservations Team
HarbourView Hotel