# Login Test Cases

| ID | Title | Preconditions | Steps | Expected Result |
|----|-------|---------------|-------|-----------------|
| LOGIN-001 | Verify Login page loads successfully | User is on the website | 1. Navigate to the Login page. | The Login page loads successfully without errors. All login elements are displayed correctly. | 
| LOGIN-002 | Login with valid credentials | User is on Login page | 1. Enter valid email<br> 2. Enter valid password<br> 3. Click Login | User is successfully logged in and redirected to Products page |
| LOGIN-003 | Verify login with invalid email | User is on the Login page | 1. Enter an invalid email address.<br>2. Enter a valid password.<br> 3. Click Login. | Login is rejected and an appropriate error message is displayed. | 
| LOGIN-004 | Login with invalid password | User opened Login page | 1. Enter username<br> 2. Enter wrong password<br> 3. Click Login | Error message is displayed. User remains on Login page |
| LOGIN-005 | Login with empty password | User opened Login page | 1. Enter username<br> 2. Leave password empty<br> 3. Click Login | Login is rejected and the user is informed that the password field is required. |
| LOGIN-006 | Login with empty email | User opened Login page | 1. Leave username empty<br> 2. Enter password<br> 3. Click Login | Login is rejected and the user is informed that the email field is required. |
| LOGIN-007 | Login with empty credentials | User opened Login page | 1. Click Login without entering data | Login is rejected and validation messages are displayed for the required fields. |
| LOGIN-008 | Verify password field masks entered characters | User is on the Login page | 1. Enter a password into the password field. | Password characters are hidden (masked) while typing. | 
| LOGIN-009 | Verify Forgot Password link works correctly | User is on the Login page | 1. Click the Forgot Password link. | User is redirected to the Password Recovery page or the password recovery process starts successfully. | 
| LOGIN-010 | Verify Logout works correctly | User is logged in | 1. Click the Logout button or menu option. | User is successfully logged out and redirected to the expected page. The protected pages are no longer accessible without logging in again. | 
| LOGIN-011 | Verify user session remains active after page refresh | User is logged in | 1. Refresh the current page. | User remains logged in after the page refresh. The current session is preserved. | 
| LOGIN-012 | Verify error message is displayed correctly | User is on the Login page | 1. Enter invalid login credentials.<br> 2. Click Login.	 | Error message is displayed. The message accurately describes the login failure without revealing sensitive information. | 
