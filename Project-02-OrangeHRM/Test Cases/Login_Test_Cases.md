
# Login Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_001 | Verify successful login with valid credentials | User is on the OrangeHRM login page | 1. Enter a valid username.<br>2. Enter a valid password.<br>3. Click **Login**. | Username: Admin<br>Password: admin123 | User is successfully logged in and the Dashboard page is displayed. |
| TC_LOGIN_002 | Verify login with invalid password | User is on the OrangeHRM login page | 1. Enter a valid username.<br>2. Enter an invalid password.<br>3. Click **Login**. | Username: Admin<br>Password: WrongPassword123 | User should not be logged in and an appropriate error message should be displayed. |
| TC_LOGIN_003 | Verify login with empty username | User is on the OrangeHRM login page | 1. Leave the username field empty.<br>2. Enter a valid password.<br>3. Click **Login**. | Username: Empty<br>Password: admin123 | User should not be logged in and an appropriate validation message should be displayed for the username field. |
| TC_LOGIN_004 | Verify login with empty password | User is on the OrangeHRM login page | 1. Enter a valid username.<br>2. Leave the password field empty.<br>3. Click **Login**. | Username: Admin<br>Password: Empty | User should not be logged in and an appropriate validation message should be displayed for the password field. |
| TC_LOGIN_005 | Verify login with empty username and password | User is on the OrangeHRM login page | 1. Leave the username field empty.<br>2. Leave the password field empty.<br>3. Click **Login**. | Username: Empty<br>Password: Empty | User should not be logged in and appropriate validation messages should be displayed. |
