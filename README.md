# AdactinHotel

## 📌 Project Overview
This project tests the Adactin Hotel web application — a purpose-built training platform that simulates a real-world hotel booking system. The application intentionally ships in two builds:

Build 1 — Contains known defects (used to practice defect identification)
Build 2 — Defects resolved (used to validate test execution)

The goal of this project is to validate the application's core booking workflows across both builds, using a combination of manual exploration, automated regression, and load/performance analysis.

## 🔍 Testing Scope
- Manual Testing
- Exploratory and structured manual testing across core application modules including login, hotel search, booking, and order management. Build 1 is used to identify and document known defects; Build 2 is used to verify fixes.
- Selenium Automation (Java)
- Automated regression suite built using the Page Object Model (POM) design pattern. Tests cover end-to-end booking flows and are run against both builds to compare behaviour.
- Performance Testing
- JMeter test plans simulate concurrent user load on the hotel search and login endpoints to evaluate response times, throughput, and system stability under stress.

## Reporting
Test reports are generated automatically after each run and saved to the /reports directory. Open the HTML report in any browser:


## 🛠️ Tools & Tech Stack

- Automation Language: Java
- Browser Automation: Selenium WebDriver
- Test Framework: TestNG
- Build Tool: Maven
- Reporting: ExtentReports / TestNG Reports
- Performance Testing: Apache JMeter
- IDE: IntelliJ IDEA / Eclipse
- Version Control: Git & GitHub
- Browser: Google Chrome + ChromeDriver
