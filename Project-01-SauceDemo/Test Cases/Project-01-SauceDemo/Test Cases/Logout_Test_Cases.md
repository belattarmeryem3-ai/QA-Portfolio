# Logout Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_LOGOUT_001 | Verify successful logout | User is logged in | 1. Click the menu button.<br>2. Click **Logout**. | N/A | User is logged out and redirected to the Login page. |
| TC_LOGOUT_002 | Verify Login page URL after logout | User is logged in | 1. Perform logout. | N/A | URL contains **/index.html**. |
| TC_LOGOUT_003 | Verify user cannot access the Products page after logout | User has logged out | 1. Logout.<br>2. Enter **/inventory.html** in the browser address bar. | N/A | User is redirected to the Login page. |
| TC_LOGOUT_004 | Verify user cannot access the Cart page after logout | User has logged out | 1. Logout.<br>2. Enter **/cart.html** in the browser address bar. | N/A | User is redirected to the Login page. |
| TC_LOGOUT_005 | Verify user cannot access the Checkout page after logout | User has logged out | 1. Logout.<br>2. Enter **/checkout-step-one.html** in the browser address bar. | N/A | User is redirected to the Login page. |
| TC_LOGOUT_006 | Verify session is terminated after logout | User is logged in | 1. Logout.<br>2. Click the browser Back button. | N/A | User cannot return to authenticated pages without logging in again. |
| TC_LOGOUT_007 | Verify logout option is available in the menu | User is logged in | 1. Click the menu button. | N/A | Logout option is displayed in the menu. |
| TC_LOGOUT_008 | Verify logout works after adding products to the cart | User has added products to the cart | 1. Add products.<br>2. Logout. | N/A | User is logged out successfully. |
| TC_LOGOUT_009 | Verify user can log in again after logout | User has logged out | 1. Enter valid username and password.<br>2. Click **Login**. | Username: standard_user<br>Password: secret_sauce | User is logged in successfully and redirected to the Products page. |
| TC_LOGOUT_010 | Verify shopping cart is reset after a new login | User logged out after adding products | 1. Logout.<br>2. Log in again. | Username: standard_user<br>Password: secret_sauce | Shopping cart is displayed according to the application's expected behavior. |
