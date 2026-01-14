# TC-LOGIN-008: Account lockout after multiple failed login attempts

## Preconditions
- Login page is accessible  
- Valid username exists  
- User is not currently locked out  

## Steps
1. Navigate to the login page: https://www.saucedemo.com/  
2. Enter a valid username in the **Username** field  
3. Enter an incorrect password in the **Password** field  
4. Click the **Login** button  
5. Repeat steps 3 and 4 using different incorrect passwords **10 times**

## Expected Results
- User is temporarily locked out after reaching the maximum number of failed login attempts  
- Login is disabled or blocked for the user  
- System displays an appropriate error or lockout message  

## Actual Result
- System does not lock the user after multiple failed login attempts  
- User is still able to continue entering passwords  
