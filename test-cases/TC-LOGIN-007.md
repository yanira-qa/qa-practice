# TC-LOGIN-007: Login fails when username case does not match exactly

**Test Case ID:** TC-LOGIN-007  
**Test Type:** Negative / Validation  

---

## Preconditions
- User is on the login page
- A valid user account exists
- System requires exact username case matching

---

## Steps to Reproduce
1. Go to the login page: https://www.saucedemo.com/
2. Enter a valid username with one letter in uppercase (e.g., `Standard_user`)
3. Enter the valid password
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
