# Test Cases for Practice

## Module 1: User Login

| TC ID | Test Scenario                                  | Test Steps                                            | Expected Result                               | Actual Result | Status | Remarks          |
|-------|-----------------------------------------------|-------------------------------------------------------|-----------------------------------------------|---------------|--------|------------------|
| TC01  | Verify login with valid email and password    | 1. Navigate to Login page<br>2. Enter valid email<br>3. Enter valid password<br>4. Click "Login" button | User is successfully logged in and redirected to the dashboard |               |        |                  |
| TC02  | Verify login with invalid email                | 1. Navigate to Login page<br>2. Enter invalid email format<br>3. Enter valid password<br>4. Click "Login" | Error message "Invalid email or password" displayed |               |        |                  |
| TC03  | Verify login with invalid password             | 1. Navigate to Login page<br>2. Enter valid email<br>3. Enter invalid password<br>4. Click "Login" | Error message "Invalid email or password" displayed |               |        |                  |
| TC04  | Verify login with empty email and password     | 1. Navigate to Login page<br>2. Leave email and password fields empty<br>3. Observe "Login" button | Login button is disabled or error messages prompt user to fill fields |               |        |                  |
| TC05  | Verify "Forgot Password" link functionality    | 1. Navigate to Login page<br>2. Click on "Forgot Password" link | User is redirected to password recovery page or popup appears |               |        |                  |
| TC06  | Verify error message on invalid credentials    | 1. Navigate to Login page<br>2. Enter invalid email or password<br>3. Click "Login" | Clear and specific error message is displayed |               |        |                  |
| TC07  | Verify login redirects to user dashboard       | 1. Login with valid credentials | User lands on the dashboard/homepage |               |        |                  |
| TC08  | Verify password masking in input field         | 1. Navigate to Login page<br>2. Enter password | Password characters appear as masked (e.g., bullets or asterisks) |               |        |                  |
| TC09  | Verify login button disabled until fields filled | 1. Navigate to Login page<br>2. Enter email or password partially or leave empty | Login button remains disabled until both fields are filled |               |        |                  |
| TC10  | Verify session timeout after inactivity        | 1. Login successfully<br>2. Stay inactive for predefined time (e.g., 15 minutes) | User session expires and user is logged out or prompted to login again |               |        |                  |

## Module 2: User Registration

| TC ID | Test Scenario                                  | Test Steps                                            | Expected Result                               | Actual Result | Status | Remarks          |
|-------|-----------------------------------------------|-------------------------------------------------------|-----------------------------------------------|---------------|--------|------------------|
| TC11  | Verify registration with valid details        | 1. Navigate to Registration page<br>2. Fill valid data in all required fields<br>3. Accept terms and conditions<br>4. Submit the form | Registration successful message is displayed and user redirected accordingly |               |        |                  |
| TC12  | Verify registration with existing email       | 1. Navigate to Registration page<br>2. Enter an email that already exists<br>3. Fill other required fields<br>4. Submit the form | Error message "Email already exists" is displayed |               |        |                  |
| TC13  | Verify password strength validation            | 1. Navigate to Registration page<br>2. Enter a weak password (e.g., less than 6 characters)<br>3. Submit the form | Warning/error about password strength is displayed |               |        |                  |
| TC14  | Verify mandatory fields validation             | 1. Navigate to Registration page<br>2. Leave mandatory fields empty<br>3. Submit the form | Error messages displayed for all empty mandatory fields |               |        |                  |
| TC15  | Verify email format validation                  | 1. Navigate to Registration page<br>2. Enter invalid email format (e.g., missing "@" or domain)<br>3. Submit the form | Error message about invalid email format displayed |               |        |                  |
| TC16  | Verify registration success message            | 1. Complete registration with valid details<br>2. Submit the form | Success message appears confirming registration |               |        |                  |
| TC17  | Verify CAPTCHA functionality (if applicable)   | 1. Navigate to Registration page<br>2. Try submitting form without solving CAPTCHA | Form submission blocked, CAPTCHA validation error displayed |               |        |                  |
| TC18  | Verify terms and conditions checkbox is mandatory | 1. Navigate to Registration page<br>2. Leave terms and conditions unchecked<br>3. Submit the form | Error message prompts user to accept terms |               |        |                  |
| TC19  | Verify error messages on invalid inputs        | 1. Enter invalid data in fields (e.g., special characters in name)<br>2. Submit the form | Proper error messages displayed near fields |               |        |                  |
| TC20  | Verify redirection after successful registration | 1. Complete registration successfully | User redirected to login page or welcome dashboard |               |        |                  |

## Module 3: User Interface (UI)

| TC ID | Test Scenario                                  | Test Steps                                            | Expected Result                               | Actual Result | Status | Remarks          |
|-------|-----------------------------------------------|-------------------------------------------------------|-----------------------------------------------|---------------|--------|------------------|
| TC21  | Verify page layout consistency across browsers | 1. Open the homepage on Chrome, Firefox, Edge | Page layout is consistent and no UI elements are broken |               |        |                  |
| TC22  | Verify responsiveness on different screen sizes | 1. Open the website on desktop, tablet, and mobile | Layout adapts correctly without overlap or cut-off |               |        |                  |
| TC23  | Verify all links and buttons are clickable    | 1. Click all links and buttons on the main pages | All clickable elements respond and navigate correctly |               |        |                  |
| TC24  | Verify form input field alignment              | 1. Navigate to forms on website<br>2. Observe input fields alignment | Fields are properly aligned and consistent with design |               |        |                  |
| TC25  | Verify font size and colors meet design specifications | 1. Compare fonts and colors on main pages to design specs | Fonts and colors match design standards |               |        |                  |
| TC26  | Verify images load correctly                    | 1. Open main pages<br>2. Check if all images appear without errors | All images load properly with correct resolution |               |        |                  |
| TC27  | Verify navigation menu functionality            | 1. Click each menu item in the navigation bar | User is navigated to the correct page |               |        |                  |
| TC28  | Verify error messages are clearly visible      | 1. Trigger validation errors (e.g., submit empty form) | Error messages are clearly visible and readable |               |        |                  |
| TC29  | Verify accessibility features (keyboard navigation) | 1. Use keyboard (Tab key) to navigate through the website | Focus moves logically through clickable elements |               |        |                  |
| TC30  | Verify loading time of main pages               | 1. Open main pages<br>2. Measure loading time | Pages load within acceptable time (e.g., < 3 seconds) |               |        |                  |

---

### Note on the "Actual Result," "Status," and "Remarks" Columns

The **Actual Result**, **Status**, and **Remarks** columns are intentionally left blank prior to test execution for the following reasons:

- **Actual Result:** This column is used to document the observed outcome during test execution. Since these test cases have not yet been run, this information is currently unknown and will be completed after testing.

- **Status:** This field reflects the test case outcome once executed. Typical status values include:  
  - **Pass:** The actual result matches the expected result.  
  - **Fail:** The actual result does not match the expected result.  
  - **Blocked:** Testing could not be performed due to external factors or dependencies.  
  - **Not Executed:** The test case has not yet been run.

- **Remarks:** This optional field allows testers to add additional notes such as defect references, environment issues, or other relevant comments that provide context for the test execution.

Completing these columns during or after testing ensures accurate, clear, and traceable test documentation, aiding effective defect tracking and overall quality assurance.

---

*Prepared by:* Pratik Joshi
