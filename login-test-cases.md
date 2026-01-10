# Login – Manual Test Cases

## Test Case 1: Successful login with valid credentials
**Test Case ID:** TC_LOGIN_001  
**Preconditions:**  
- User has a registered account  
- User is on the login page  

**Steps:**  
1. Enter a valid username  
2. Enter a valid password  
3. Click the **Login** button  

**Expected Result:**  
- User is successfully logged in  
- User is redirected to the dashboard/home page  

---

## Test Case 2: Login with invalid password
**Test Case ID:** TC_LOGIN_002  
**Preconditions:**  
- User has a registered account  
- User is on the login page  

**Steps:**  
1. Enter a valid username  
2. Enter an invalid password  
3. Click the **Login** button  

**Expected Result:**  
- Error message is displayed  
- User remains on the login page  

---

## Test Case 3: Login with empty fields
**Test Case ID:** TC_LOGIN_003  
**Preconditions:**  
- User is on the login page  

**Steps:**  
1. Leave username empty  
2. Leave password empty  
3. Click the **Login** button  

**Expected Result:**  
- Validation message is shown  
- Login is not performed  

---

## Test Case 4: Password field masking
**Test Case ID:** TC_LOGIN_004  
**Preconditions:**  
- User is on the login page  

**Steps:**  
1. Type a password in the password field  

**Expected Result:**  
- Password characters are masked (e.g., displayed as dots or asterisks)  
