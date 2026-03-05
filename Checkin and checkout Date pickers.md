## Defect ID: DEF-001
- Module: Search Hotel
- Summary: Check-in and Check-out date fields accept invalid date (30 February)
- Steps to Reproduce:

- Navigate to https://adactinhotelapp.com
- Login with valid credentials
- On the Search Hotel page, enter 30/02/2026 in the Check-in Date field
- Enter 02/03/2026 in the Check-out Date field
- Click Search

- Expected Result: System should display a validation error — date does not exist
- Actual Result: System accepts 30 February as a valid date and proceeds with the search
- Severity: Major
- Priority: High
- Build: Build 1
- Status: Open
