# Bug Reports

| Bug ID | Bug Title | Severity | Priority | Environment | Steps to Reproduce | Expected Result | Actual Result | Status |
|--------|-----------|----------|----------|-------------|--------------------|-----------------|---------------|--------|
| BUG_001 | Product image is displayed incorrectly for problem_user | Medium | Medium | Windows 11, Chrome | 1. Log in with **problem_user**.<br>2. Open the Products page. | Each product should display the correct image. | Some product images do not match their corresponding products. | Open |
| BUG_002 | Checkout button is slow when using performance_glitch_user | Low | Low | Windows 11, Chrome | 1. Log in with **performance_glitch_user**.<br>2. Add a product to the cart.<br>3. Proceed to Checkout. | Checkout page should load within an acceptable time. | Checkout page takes noticeably longer to load. | Open |
| BUG_003 | Product image is broken for visual_user | Medium | Medium | Windows 11, Chrome | 1. Log in with **visual_user**.<br>2. Open the Products page. | Product images should be displayed correctly. | One or more product images are broken or displayed incorrectly. | Open |
| BUG_004 | Product layout is inconsistent for visual_user | Low | Low | Windows 11, Chrome | 1. Log in with **visual_user**.<br>2. Observe the Products page. | Product layout should be aligned consistently. | Some UI elements are misaligned. | Open |
| BUG_005 | Product sorting does not work correctly for problem_user | High | High | Windows 11, Chrome | 1. Log in with **problem_user**.<br>2. Sort products by **Price (Low to High)**. | Products should be sorted correctly by price. | Products are displayed in the wrong order. | Open |
