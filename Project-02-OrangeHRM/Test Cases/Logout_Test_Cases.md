# Logout Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGOUT_001 | Verify successful logout | User is logged in | 1. Click the user profile menu.<br>2. Click **Logout**. | N/A | User is logged out and redirected to the Login page. |
| TC_LOGOUT_002 | Verify login page is displayed after logout | User has logged out | 1. Observe the current page. | N/A | OrangeHRM Login page is displayed. |
| TC_LOGOUT_003 | Verify user cannot access Dashboard after logout using browser Back | User has logged out | 1. Click the browser Back button. | N/A | User should not regain access to the authenticated Dashboard without logging in again. |
