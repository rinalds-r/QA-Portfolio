# Login Test Cases

| ID | Title | Preconditions | Steps | Expected Result | Priority |
|----|-------|---------------|-------|-----------------|----------|
| TC-001 | Login with valid credentials | User is on Login page | 1. Enter valid username 2. Enter valid password 3. Click Login | User is successfully logged in and redirected to Products page | High |
| TC-002 | Login with invalid password | User opened Login page | 1. Enter username 2. Enter wrong password 3. Click Login | Error message is displayed. User remains on Login page | High |
| TC-003 | Login with empty password | User opened Login page | 1. Enter username 2. Leave password empty 3. Click Login | Validation message is displayed | High |
| TC-004 | Login with empty username | User opened Login page | 1. Leave username empty 2. Enter password 3. Click Login | Validation message is displayed | High |
| TC-005 | Login with empty credentials | User opened Login page | Click Login without entering data | Validation message is displayed | High |
