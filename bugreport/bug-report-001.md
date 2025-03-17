# Bug Report: System allows creating an account with too short username and password on DemoBlaze

**Issue Description:**  
The system allows the creation of an account with a username and password that are too short (only 1 letter and 1 number). The system should show an error message indicating that the username or password is invalid.

## Steps to Reproduce:
1. Go to [DemoBlaze](https://www.demoblaze.com/index.html).
2. Click on the "Sign Up" link in the upper-right corner.
3. Enter a username of one letter and a password of one number.
4. Click the "Sign Up" button.
5. The system shows a "Sign up successful" message, even with invalid credentials.

## Expected Result:
The system should display an error message saying the username or password is too short.

## Actual Result:
The system allows the creation of the account and shows a "Sign up successful" message despite invalid credentials.

**Severity:** High  
**Priority:** High

