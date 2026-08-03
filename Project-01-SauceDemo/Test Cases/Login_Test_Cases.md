# Login Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_001 | Verify successful login with valid credentials | User is on the login page | 1. Enter a valid username.<br>2. Enter a valid password.<br>3. Click **Login**. | Username: standard_user<br>Password: secret_sauce | User is successfully logged in and redirected to the Products page. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_002 | Verify that the user cannot log in with an invalid password | User is on the login page | 1. Enter a valid username.<br>2. Enter an invalid password.<br>3. Click **Login**. | Username: standard_user<br>Password: secret_sauce01 | The user remains on the login page and an appropriate error message is displayed "Username and password do not match any user in this service". |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_003 | Verify that the user cannot log in with an empty username | User is on the login page | 1. Leave the username field empty.<br>2. Enter a valid password.<br>3. Click **Login**. | Username: (empty)<br>Password: secret_sauce | The user remains on the login page and the message "Username is required" is displayed. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_004 | Verify that the user cannot log in with an empty password | User is on the login page | 1. Enter a valid username.<br>2. Leave the password field empty.<br>3. Click **Login**. | Username: standard_user<br>Password: (empty) | The user remains on the login page and the message "Password is required" is displayed. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_005 | Verify that the user cannot log in with both username and password empty | User is on the login page | 1. Leave the username field empty.<br>2. Leave the password field empty.<br>3. Click **Login**. | Username: (empty)<br>Password: (empty) | The user remains on the login page and the message "Username is required" is displayed. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_006 | Verify that a locked user cannot log in | User is on the login page | 1. Enter username **locked_out_user**.<br>2. Enter password **secret_sauce**.<br>3. Click **Login**. | Username: locked_out_user<br>Password: secret_sauce | The user remains on the login page and the message "Sorry, this user has been locked out." is displayed. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_007 | Verify successful login with problem_user | User is on the login page | 1. Enter username **problem_user**.<br>2. Enter password **secret_sauce**.<br>3. Click **Login**. | Username: problem_user<br>Password: secret_sauce | User is successfully logged in and redirected to the Products page. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_008 | Verify successful login with performance_glitch_user | User is on the login page | 1. Enter username **performance_glitch_user**.<br>2. Enter password **secret_sauce**.<br>3. Click **Login**. | Username: performance_glitch_user<br>Password: secret_sauce | User is successfully logged in and redirected to the Products page. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_009 | Verify login using a username with leading and trailing spaces | User is on the login page | 1. Enter username ** standard_user **.<br>2. Enter password **secret_sauce**.<br>3. Click **Login**. | Username: " standard_user "<br>Password: secret_sauce | Login is rejected and an appropriate error message is displayed. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_010 | Verify login using a username with different letter casing | User is on the login page | 1. Enter username **Standard_User**.<br>2. Enter password **secret_sauce**.<br>3. Click **Login**. | Username: Standard_User<br>Password: secret_sauce | Login is rejected and an appropriate error message is displayed. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_011 | Verify login with SQL injection text in the username field | User is on the login page | 1. Enter username **' OR '1'='1**.<br>2. Enter password **secret_sauce**.<br>3. Click **Login**. | Username: ' OR '1'='1<br>Password: secret_sauce | Login is rejected and no unauthorized access is granted. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_012 | Verify login using special characters in the username | User is on the login page | 1. Enter username **@#$%^&***.<br>2. Enter password **secret_sauce**.<br>3. Click **Login**. | Username: @#$%^&*<br>Password: secret_sauce | Login is rejected and an appropriate error message is displayed. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_013 | Verify that the password field masks entered characters | User is on the login page | 1. Enter any password in the password field. | Password: secret_sauce | Password characters are displayed as masked (••••••••). |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_014 | Verify login by pressing the Enter key | User is on the login page | 1. Enter a valid username.<br>2. Enter a valid password.<br>3. Press **Enter**. | Username: standard_user<br>Password: secret_sauce | User is successfully logged in and redirected to the Products page. |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGIN_015 | Verify that the error message disappears after a successful login | User is on the login page | 1. Perform an invalid login.<br>2. Correct the credentials.<br>3. Click **Login**. | Username: standard_user<br>Password: secret_sauce | User is successfully logged in and no previous error message is displayed. |
