## Defect ID: DEF-003

- Defect Type: Functional / UI Defect
- Phase Found: Testing — Confirmation Page
- Module: Booking Confirmation

## Summary

- Check-in and check-out dates are displayed as “arrival” and “departure” on the confirmation page, using flight terminology instead of hotel terminology. This may confuse users.

## Description

- On the booking confirmation page, the system shows:
- Arrival Date instead of Check-in Date
- Departure Date instead of Check-out Date
- The check-in/check-out flow works correctly during booking, but the terminology changes on confirmation.
- This inconsistency may confuse users and reduce trust in the system.

## Impact

- Users may misinterpret hotel booking dates.
- Could lead to booking errors or customer support issues.
- Reduces overall usability and consistency of the application.

## Expected Result

- Confirmation page should display Check-in Date and Check-out Date, consistent with the booking flow.

## Actual Result

- Confirmation page displays Arrival Date and Departure Date, using flight booking terminology.

- Severity: Minor
- Priority: Medium
- Phase: Testing
- Status: Open
