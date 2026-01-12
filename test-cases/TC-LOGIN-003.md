# Test Case: Login Validation – Leading Spaces

## Test Case ID
TC-LOGIN-003

## Module
Login

## Test Type
Functional / Negative

---

## Preconditions
- User is on the SauceDemo login page
- Valid login credentials are available:
  - **Username:** standard_user
  - **Password:** secret_sauce

---

## Steps to Reproduce
1. Open the login page: https://www.saucedemo.com/
2. In the username field, press the space bar twice, then enter the valid username.
3. Enter the valid password.
4. Click the **Login** button.

---

## Expected Result
System displays a validation error message indicating invalid input.

---

## Actual Result
System displays the correct validation error message.
