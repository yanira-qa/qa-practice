## Test Case: Login displays validation message when username contains trailing spaces

**Test Case ID:** TC-LOGIN-001  
**Module:** Login  
**Test Type:** Functional / Negative  

### Preconditions
- User is on the SauceDemo login page
- Valid login credentials are available:
  - Username: standard_user
  - Password: secret_sauce

### Test Steps
1. Open the login page: https://www.saucedemo.com/
2. Enter the provided username and press the space bar twice to add trailing spaces
3. Enter the provided password
4. Click on the "Login" button

### Expected Result
The system displays a validation error message indicating invalid input.

### Actual Result
The system displays the correct validation error message.

### Test Status
Pass

### Environment
- OS: Windows 11
- Browser: Brave (latest)
- Device: Desktop

