# Cart Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_CART_001 | Verify shopping cart page opens successfully | User is logged in | 1. Click the shopping cart icon. | N/A | Shopping Cart page is displayed successfully. |
| TC_CART_002 | Verify added product is displayed in the shopping cart | User has added one product | 1. Click the shopping cart icon. | Sauce Labs Backpack | The added product is displayed in the shopping cart. |
| TC_CART_003 | Verify multiple products are displayed in the shopping cart | User has added multiple products | 1. Add three different products.<br>2. Click the shopping cart icon. | N/A | All selected products are displayed in the shopping cart. |
| TC_CART_004 | Verify product name is displayed in the shopping cart | User has added a product | 1. Open the shopping cart. | N/A | Product name is displayed correctly. |
| TC_CART_005 | Verify product description is displayed in the shopping cart | User has added a product | 1. Open the shopping cart. | N/A | Product description is displayed correctly. |
| TC_CART_006 | Verify product price is displayed in the shopping cart | User has added a product | 1. Open the shopping cart. | N/A | Product price is displayed correctly. |
| TC_CART_007 | Verify product quantity is displayed in the shopping cart | User has added a product | 1. Open the shopping cart. | N/A | Product quantity is displayed correctly. |
| TC_CART_008 | Verify removing a product from the shopping cart | User has at least one product in the cart | 1. Open the shopping cart.<br>2. Click **Remove**. | Sauce Labs Backpack | Product is removed from the shopping cart. |
| TC_CART_009 | Verify shopping cart badge updates after removing a product | User has one product in the cart | 1. Remove the product. | N/A | The shopping cart badge is updated correctly. |
| TC_CART_010 | Verify Continue Shopping button functionality | User is on the Shopping Cart page | 1. Click **Continue Shopping**. | N/A | User is redirected to the Products page. |
| TC_CART_011 | Verify Checkout button functionality | User has at least one product in the cart | 1. Click **Checkout**. | N/A | User is redirected to the Checkout Information page. |
| TC_CART_012 | Verify shopping cart is empty when no products are added | User is logged in | 1. Open the shopping cart without adding products. | N/A | The shopping cart is displayed as empty. |
| TC_CART_013 | Verify removed product does not reappear after refreshing the page | User removed a product from the cart | 1. Remove a product.<br>2. Refresh the page. | N/A | The removed product is not displayed after refresh. |
| TC_CART_014 | Verify clicking the product name opens the Product Details page | User has a product in the cart | 1. Click the product name. | Sauce Labs Backpack | Product Details page is displayed successfully. |
| TC_CART_015 | Verify clicking the product image opens the Product Details page | User has a product in the cart | 1. Click the product image. | Sauce Labs Backpack | Product Details page is displayed successfully. |
| TC_CART_016 | Verify user can proceed to checkout with multiple products | User has multiple products in the cart | 1. Click **Checkout**. | N/A | Checkout Information page is displayed successfully. |
| TC_CART_017 | Verify shopping cart contents are preserved after navigating back to the Products page | User has added products to the cart | 1. Click **Continue Shopping**.<br>2. Return to the shopping cart. | N/A | Previously added products remain in the shopping cart. |
| TC_CART_018 | Verify shopping cart badge displays the correct number of products | User has added multiple products | 1. Add three products.<br>2. Observe the cart badge. | N/A | The shopping cart badge displays the correct number of products. |
| TC_CART_019 | Verify user can remove all products from the shopping cart | User has multiple products in the cart | 1. Remove all products. | N/A | The shopping cart becomes empty and the badge disappears. |
| TC_CART_020 | Verify shopping cart URL | User opens the shopping cart | 1. Click the shopping cart icon. | N/A | URL contains **/cart.html**. |
