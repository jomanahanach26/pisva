# PISVA — Product Requirements Document

**Version:** 0.1  
**Status:** Draft — UX Validation  
**Product:** PISVA  
**Tagline:** Together, nothing gets lost.

## 1. Product Vision

PISVA helps families coordinate responsibilities when supporting parents and relatives.

The central questions are:

- What has been done?
- What still needs to happen?
- Who is responsible for the next step?

## 2. Target Users

Family members who share responsibility for administrative matters, appointments, and ongoing follow-ups, initially focusing on families living in Sweden.

## 3. Core MVP Features

### Radar

A shared overview of:
- Cases requiring attention
- Overdue follow-ups
- Upcoming appointments
- Pending responsibility handoffs
- Requests for appointment accompaniment
- Cases without an assigned owner, if applicable

### Cases

Family members can create and track cases with:
- Title and optional description
- Current responsible person
- Status and next step
- Follow-up date
- Notes and updates
- Activity history

A new case initially belongs to its creator. Responsibility cannot transfer without explicit acceptance.

### Responsibility Handoffs

A current owner can request a handoff to another family member.

The recipient can accept or decline.

Until acceptance, the original owner remains responsible. Only one person can be the confirmed owner at a time.

### Appointments

Family members can:
- Create appointments
- Add time and location
- Request accompaniment
- Accept or decline accompaniment requests
- Record appointment outcomes

Only one confirmed accompanying person is assigned to an appointment at a time.

### Family Notes

Family members can leave short written notes directed to another family member and linked to a case or appointment.

Notes do not automatically create tasks or transfer responsibility.

### History and Archive

Completed cases and recorded actions remain accessible.

History should capture relevant actions, dates, outcomes, and responsibility changes.

Users can search past cases for reference.

App records are not official proof of submission, approval, or communication with authorities.

### Family Space

Users can invite family members and manage basic access permissions.

## 4. Out of Scope for the Initial MVP

- General family chat
- Voice recording and speech-to-text
- Document storage and PDF package generation
- Government or email integrations
- Payments
- AI automation

## 5. UX Principles

- Mobile-first and easy to understand
- English first, Swedish later
- Clear responsibility and explicit confirmation
- Minimal steps for common actions
- Accessible and privacy-conscious design
- Completed work remains discoverable

## 6. Success Criteria to Validate

- Users can create a case and identify its next step.
- Users understand who currently owns a case.
- Users understand that handoffs require acceptance.
- Users can request help with an appointment.
- Users can retrieve a previously completed case.

These criteria will be tested through a clickable prototype with 3–5 representative users before implementation.

## 7. Project Phase

Current phase: UX prototype and user testing.

Next phase: Technical architecture and implementation planning.