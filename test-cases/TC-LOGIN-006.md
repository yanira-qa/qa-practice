# TC-LOGIN-006: Username field rejects email format when username is required

**Test Case ID:** TC-LOGIN-006  
**Test Type:** Negative / Validation  

---

## Preconditions
- User is on the login page
- System requires a username (not an email) for authentication
- A valid user account exists

---

## Steps to Reproduce
1. Go to the login page: https://www.saucedemo.com/
2. Enter an email address in the **Username** field (e.g., `user@test.com`)
3. Enter a valid password in the **Password** field
4. Click the **Login** button

---

## Expected Result
- Login fails
- A generic error message is displayed
- User is not authenticated

---

## Actual Result
- Login fails
- Error message displayed:  
  **“Epic sadface: Username and password do not match any user in this service”**
