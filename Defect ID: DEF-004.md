## Defect ID: DEF-004

Defect Type: Requirements / UI Validation Defect
Phase Found: Testing — Booking Form
Module: Room Selection

## Summary

- The "Children per Room" field is not mandatory, allowing unrealistic bookings (e.g., booking a one-bedroom room for 4 kids).
- Most hotels require accurate guest capacity information.

## Description

- The booking form is missing mandatory validation for the "Children per Room" field.
- Users can submit a booking without specifying the number of children, even if that number would exceed room capacity.
- For instance, a user could book a single-room hotel for 30 kids, which is unrealistic.
- Typically, hotels rely on accurate guest counts for safety, space planning, and compliance with occupancy rules.

## Impact

- Users may unintentionally book rooms that cannot physically accommodate all guests.
- This could result in poor user experience, increased customer support requests, or even safety risks.
- QA cannot validate proper guest capacity rules, making the booking process unreliable.

## Expected Result

- The "Children per Room" field should be mandatory.
- Validation logic should enforce realistic occupancy constraints—for example, preventing booking if the number of children plus adults exceeds a room’s capacity.
- Clear messaging should inform users that all guest counts (including children) must be provided.
- Actual Result

## The field is optional, and no validation prevents unrealistic booking combinations.

Severity: Major
Priority: High
Phase: Testing
Status: Open
