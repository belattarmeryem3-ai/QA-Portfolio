# Checkout Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_CHECKOUT_001 | Verify navigation to Checkout Information page | User has at least one product in the cart | 1. Open the shopping cart.<br>2. Click **Checkout**. | N/A | Checkout Information page is displayed. |
| TC_CHECKOUT_002 | Verify checkout with valid information | User is on the Checkout Information page | 1. Enter valid First Name.<br>2. Enter valid Last Name.<br>3. Enter valid Postal Code.<br>4. Click **Continue**. | First Name: Maryam<br>Last Name: Ahmed<br>Postal Code: 40000 | User is redirected to the Checkout Overview page. |
| TC_CHECKOUT_003 | Verify checkout with an empty First Name | User is on the Checkout Information page | 1. Leave the First Name field empty.<br>2. Enter Last Name.<br>3. Enter Postal Code.<br>4. Click **Continue**. | First Name: (empty)<br>Last Name: Ahmed<br>Postal Code: 40000 | The message **"First Name is required"** is displayed. |
| TC_CHECKOUT_004 | Verify checkout with an empty Last Name | User is on the Checkout Information page | 1. Enter First Name.<br>2. Leave the Last Name field empty.<br>3. Enter Postal Code.<br>4. Click **Continue**. | First Name: Maryam<br>Last Name: (empty)<br>Postal Code: 40000 | The message **"Last Name is required"** is displayed. |
| TC_CHECKOUT_005 | Verify checkout with an empty Postal Code | User is on the Checkout Information page | 1. Enter First Name.<br>2. Enter Last Name.<br>3. Leave Postal Code empty.<br>4. Click **Continue**. | First Name: Maryam<br>Last Name: Ahmed<br>Postal Code: (empty) | The message **"Postal Code is required"** is displayed. |
| TC_CHECKOUT_006 | Verify Cancel button functionality | User is on the Checkout Information page | 1. Click **Cancel**. | N/A | User is redirected to the Shopping Cart page. |
| TC_CHECKOUT_007 | Verify Checkout Overview page displays selected products | User completed Checkout Information successfully | 1. Proceed to Checkout Overview. | N/A | All selected products are displayed correctly. |
| TC_CHECKOUT_008 | Verify product price is displayed on Checkout Overview page | User is on the Checkout Overview page | 1. Observe product prices. | N/A | Product prices are displayed correctly. |
| TC_CHECKOUT_009 | Verify item total is calculated correctly | User has multiple products in checkout | 1. Observe Item Total. | N/A | Item Total equals the sum of all product prices. |
| TC_CHECKOUT_010 | Verify tax amount is displayed | User is on the Checkout Overview page | 1. Observe Tax value. | N/A | Tax amount is displayed correctly. |
| TC_CHECKOUT_011 | Verify total amount is calculated correctly | User is on the Checkout Overview page | 1. Observe Total value. | N/A | Total equals Item Total plus Tax. |
| TC_CHECKOUT_012 | Verify Finish button completes the order | User is on the Checkout Overview page | 1. Click **Finish**. | N/A | Order is completed successfully. |
| TC_CHECKOUT_013 | Verify successful order confirmation page | User completed the checkout process | 1. Complete checkout. | N/A | Checkout Complete page is displayed with a success message. |
| TC_CHECKOUT_014 | Verify Back Home button functionality | User is on the Checkout Complete page | 1. Click **Back Home**. | N/A | User is redirected to the Products page. |
| TC_CHECKOUT_015 | Verify Cancel button on Checkout Overview page | User is on the Checkout Overview page | 1. Click **Cancel**. | N/A | User is redirected to the Products page. |
| TC_CHECKOUT_016 | Verify product quantity is displayed on Checkout Overview page | User has multiple products | 1. Observe product quantity. | N/A | Product quantity is displayed correctly. |
| TC_CHECKOUT_017 | Verify Checkout Information page URL | User clicks Checkout | 1. Click **Checkout**. | N/A | URL contains **/checkout-step-one.html**. |
| TC_CHECKOUT_018 | Verify Checkout Overview page URL | User clicks Continue after entering valid information | 1. Complete Checkout Information.<br>2. Click **Continue**. | Valid customer information | URL contains **/checkout-step-two.html**. |
| TC_CHECKOUT_019 | Verify Checkout Complete page URL | User completes checkout successfully | 1. Click **Finish**. | N/A | URL contains **/checkout-complete.html**. |
| TC_CHECKOUT_020 | Verify order completion message is displayed | User completes checkout | 1. Complete the checkout process. | N/A | The message **"Thank you for your order!"** is displayed. |
