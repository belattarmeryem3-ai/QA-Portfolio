
# Product Test Cases

| Test Case ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|--------------|-----------------|---------------|------------|-----------|-----------------|
| TC_PRODUCT_001 | Verify all products are displayed after successful login | User is logged in | 1. Log in with valid credentials. | Username: standard_user<br>Password: secret_sauce | All available products are displayed on the Products page. |
| TC_PRODUCT_002 | Verify each product displays a name | User is on the Products page | 1. Observe all products. | N/A | Every product has a visible name. |
| TC_PRODUCT_003 | Verify each product displays a price | User is on the Products page | 1. Observe all products. | N/A | Every product has a visible price. |
| TC_PRODUCT_004 | Verify each product displays an image | User is on the Products page | 1. Observe all products. | N/A | Every product has an image. |
| TC_PRODUCT_005 | Verify Add to Cart button is displayed for each product | User is on the Products page | 1. Observe each product. | N/A | Each product displays an Add to Cart button. |
| TC_PRODUCT_006 | Verify adding a product to the cart | User is on the Products page | 1. Click **Add to Cart** for any product. | Sauce Labs Backpack | Product is added to the cart and the button changes to **Remove**. |
| TC_PRODUCT_007 | Verify removing a product from the Products page | User has added a product to the cart | 1. Click **Remove**. | Sauce Labs Backpack | Product is removed from the cart and the button changes back to **Add to Cart**. |
| TC_PRODUCT_008 | Verify shopping cart badge updates after adding a product | User is on the Products page | 1. Add one product to the cart. | N/A | Cart badge displays **1**. |
| TC_PRODUCT_009 | Verify multiple products can be added to the cart | User is on the Products page | 1. Add three different products. | N/A | Cart badge displays **3**. |
| TC_PRODUCT_010 | Verify sorting products by Name (A to Z) | User is on the Products page | 1. Select **Name (A to Z)** from the sort menu. | N/A | Products are sorted alphabetically from A to Z. |
| TC_PRODUCT_011 | Verify sorting products by Name (Z to A) | User is on the Products page | 1. Select **Name (Z to A)** from the sort menu. | N/A | Products are sorted alphabetically from Z to A. |
| TC_PRODUCT_012 | Verify sorting products by Price (Low to High) | User is on the Products page | 1. Select **Price (Low to High)**. | N/A | Products are sorted by ascending price. |
| TC_PRODUCT_013 | Verify sorting products by Price (High to Low) | User is on the Products page | 1. Select **Price (High to Low)**. | N/A | Products are sorted by descending price. |
| TC_PRODUCT_014 | Verify opening the Product Details page by clicking the product name | User is on the Products page | 1. Click any product name. | Sauce Labs Backpack | Product Details page is displayed. |
| TC_PRODUCT_015 | Verify opening the Product Details page by clicking the product image | User is on the Products page | 1. Click the product image. | Sauce Labs Backpack | Product Details page is displayed. |
| TC_PRODUCT_016 | Verify Back to Products button on the Product Details page | User is on the Product Details page | 1. Click **Back to Products**. | N/A | User is redirected to the Products page. |
| TC_PRODUCT_017 | Verify Add to Cart from the Product Details page | User is on the Product Details page | 1. Click **Add to Cart**. | Sauce Labs Backpack | Product is added to the cart successfully. |
| TC_PRODUCT_018 | Verify Remove from the Product Details page | User has added the product to the cart | 1. Click **Remove**. | Sauce Labs Backpack | Product is removed from the cart successfully. |
| TC_PRODUCT_019 | Verify shopping cart icon is always visible | User is logged in | 1. Observe the top-right corner. | N/A | Shopping cart icon is visible. |
| TC_PRODUCT_020 | Verify Inventory page URL after login | User logs in successfully | 1. Log in using valid credentials. | Username: standard_user<br>Password: secret_sauce | URL contains **/inventory.html**. |
