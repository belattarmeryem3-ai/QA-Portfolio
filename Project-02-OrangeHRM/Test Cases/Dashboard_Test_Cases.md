# Dashboard Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_DASHBOARD_001 | Verify successful navigation to Dashboard after login | User is on the OrangeHRM login page | 1. Enter valid username.<br>2. Enter valid password.<br>3. Click **Login**. | Username: Admin<br>Password: admin123 | User is successfully logged in and the Dashboard page is displayed. |
| TC_DASHBOARD_002 | Verify Dashboard elements are displayed after login | User is successfully logged in and on the Dashboard page | 1. Observe the Dashboard page.<br>2. Check the main navigation menu and Dashboard content. | N/A | The main Dashboard elements and navigation menu are displayed correctly. |
| TC_DASHBOARD_003 | Verify Dashboard navigation menu is displayed | User is on the Dashboard page | 1. Observe the left-side navigation menu. | N/A | The navigation menu is displayed correctly and available to the user. |
| TC_DASHBOARD_004 | Verify user can access Employee Management from Dashboard | User is on the Dashboard page | 1. Click **PIM** from the navigation menu. | N/A | User is redirected to the Employee Management page. |
| TC_DASHBOARD_005 | Verify user profile menu is displayed | User is logged in | 1. Observe the top-right corner of the Dashboard. | N/A | The logged-in user's profile menu is displayed. |
