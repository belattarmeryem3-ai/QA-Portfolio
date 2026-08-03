# Login Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_001 | Verify successful login with valid credentials | User is on the login page | 1. Enter a valid username.<br>2. Enter a valid password.<br>3. Click **Login**. | Username: standard_user<br>Password: secret_sauce | User is successfully logged in and redirected to the Products page. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_002 | Verify that the user cannot log in with an invalid password | User is on the login page | 1. Enter a valid username.<br>2. Enter an invalid password.<br>3. Click **Login**. | Username: standard_user<br>Password: secret_sauce01 | The user remains on the login page and an appropriate error message is displayed. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_003 | Verify that the user cannot log in with an empty username | User is on the login page | 1. Leave the username field empty.<br>2. Enter a valid password.<br>3. Click **Login**. | Username: (empty)<br>Password: secret_sauce | The user remains on the login page and the message "Username is required" is displayed. |
