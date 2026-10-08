# PISVA — User Flows

**Version:** 0.1  
**Status:** Draft — UX Validation  
**Language:** English (Swedish planned later)

## 1. Navigation

The application has four main sections:

- **Radar:** Overview of items requiring attention.
- **Cases:** Active, completed, and archived cases.
- **Appointments:** Upcoming and past appointments.
- **Family:** Members and family-space management.

Notes belong to cases or appointments. History is accessible through Cases and individual records.

## 2. Create a Case

1. Open Radar or Cases.
2. Select **New Case**.
3. Enter a title.
4. Optionally add a description and follow-up date.
5. Save the case.
6. The creator becomes the initial confirmed owner.
7. The new case appears in Cases.

**Expected outcome:** The family can identify the current owner and the next action.

## 3. Update a Case

1. Open a case.
2. Select **Add Update**.
3. Record what happened and the outcome.
4. Optionally specify the next action and follow-up date.
5. Save.

**Expected outcome:** The update appears in the activity history and remains available for future reference.

## 4. Transfer Responsibility

1. The current owner opens the case.
2. Selects **Request Handoff**.
3. Chooses a family member.
4. Sends the request.
5. The recipient reviews the case and chooses **Accept** or **Decline**.
6. Only after acceptance does the recipient become the confirmed owner.

**Important rules:**

- The original owner stays responsible while the request is pending.
- Declining a request does not change ownership.
- A case has only one confirmed owner at a time.

## 5. Create an Appointment

1. Open Appointments.
2. Select **New Appointment**.
3. Enter title, date, time, and optional location.
4. Save.
5. The appointment appears in the calendar/list.

## 6. Request Accompaniment

1. Open an appointment.
2. Select **Request Escort**.
3. Choose a family member.
4. Send the request.
5. The recipient accepts or declines.
6. The appointment displays the confirmed escort only after acceptance.

**Important:** Only one confirmed escort can be assigned at a time.

## 7. Leave a Family Note

1. Open a case or appointment.
2. Select **Add Note**.
3. Choose the intended family member.
4. Write a short note.
5. Save.

**Expected outcome:** The note is linked to the relevant record and visible to authorized family members.

**Important:** A note does not automatically create a task or transfer responsibility.

## 8. Complete and Archive a Case

1. Open a case.
2. Record the outcome.
3. Select **Mark as Completed**.
4. The case moves out of the active list.
5. It remains available under Completed or Archive.
6. Authorized users can review its history.

**Expected outcome:** Completed work remains discoverable instead of disappearing.

## 9. Find a Past Case

1. Open Cases.
2. Select Completed or Archive.
3. Search for a case.
4. Open its details.
5. Review past actions, dates, responsibility changes, and outcomes.

## 10. UX Validation Tasks

Test the prototype with 3–5 representative users.

Ask participants to:

1. Create a case for a parent.
2. Request a handoff to another family member.
3. Leave a note for a specific person.
4. Create an appointment and request accompaniment.
5. Find a completed case from the previous month.

Record task success, confusion, hesitation, and suggestions before implementation.