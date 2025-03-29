# Hostinger Website Automation Testing

## Project Overview
This project automates the login and navigation functionalities of the Hostinger website using Selenium WebDriver with TestNG. The test suite covers login authentication and navigation to various sections like Websites, Domains, Emails, VPS, Billing, and Marketplace.

## Technologies Used
- Java
- Selenium WebDriver
- TestNG
- ChromeDriver

## Setup Instructions
1. Install Java (JDK 8 or later).
2. Install Maven.
3. Download and set up ChromeDriver.
4. Clone this repository.
5. Add the necessary dependencies in `pom.xml`.
6. Run the test suite using TestNG.

## Test Cases Implemented
### 1. Login Test
- **Description**: Verifies user authentication with valid credentials.
- **Steps**:
  1. Open the Hostinger login page.
  2. Enter a valid email and password.
  3. Click the login button.
  4. Validate successful login.
- **Expected Result**: User should be redirected to the dashboard.

### 2. Navigation Tests
- **Websites Navigation**
- **Domains Navigation**
- **Emails Navigation**
- **VPS Navigation**
- **Billing Navigation**
- **Marketplace Navigation**

## Bug Report
### Bug ID: HST-001
- **Description**: Price inconsistency when selecting different billing periods.
- **Steps to Reproduce**:
  1. Navigate to the Hostinger pricing page.
  2. Change the billing period between different options (48 months, 24 months, etc.).
  3. Observe the displayed pricing.
- **Expected Result**: The price should correctly reflect the selected billing period.
- **Actual Result**: The displayed pricing is inconsistent and does not match the selected billing period.
- **Severity**: High
- **Priority**: Medium
- **Screenshot**: Attached
- **Suggestion**: Implement real-time price recalculations when changing billing periods to avoid user confusion.
### Bug 2: UI Responsiveness Issue
- **Description:** The website layout breaks or elements are misaligned on different mobile screen sizes.
- **Steps to Reproduce:**
  1. Open the website on multiple mobile screen sizes.
  2. Observe layout inconsistencies or broken elements.
- **Expected Result:** The website should adjust properly for all screen sizes.
- **Actual Result:** The UI elements do not render properly on different screen sizes.
- **Severity:** Medium
- **Priority:** Medium
## Execution
Run the test suite using:
```
mvn test
```

## Author
Vikash Kumar Bharti
