## TC-LOGIN-005 — Login displays validation message when password field is left empty

**Title:** Login displays validation message when password field is left empty

### Preconditions
- User is on the SauceDemo login page: https://www.saucedemo.com/
- Valid username is available:
  - Username: `standard_user`

### Test Data
- Username: `standard_user`
- Password: *(leave empty)*

### Steps to Reproduce
1. Open https://www.saucedemo.com/
2. Enter `standard_user` in the **Username** field.
3. Leave the **Password** field empty.
4. Click the **Login** button.

### Expected Result
- The system displays a validation message indicating the password is required (e.g., `Password is required`).

### Actual Result
- TBD (fill after execution)

### Environment
- OS: Windows 11  
- Browser: Chrome (latest)  
- Device: Desktop
