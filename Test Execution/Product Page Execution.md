# Product Page Execution

| Test Case | Actual Result                                                                       | Status | Bug        |
| --------- | ----------------------------------------------------------------------------------- | ------ | ---------- |
| PDP-001 | The product image is displayed correctly without distortion, missing elements, or broken image icons. | Pass | | 
| PDP-002 | The product title is displayed correctly and is clearly readable. | Pass | | 
| PDP-003 | The product description is displayed completely and is readable without formatting issues. | Pass | | 
| PDP-004 | The product price is displayed correctly using the expected currency and format. | Pass | | 
| PDP-005 | The selected variant is applied successfully. | Pass | | 
| PDP-006 | The Add to Cart button is visible, enabled, and clearly labeled. | Pass | | 
| PDP-007 | After clicking the Add to Cart button, the cart page starts loading indefinitely. The cart content is not displayed until the page is manually refreshed. The cart is updated accordingly. | Fail | BUG-004 | 
| PDP-008 | The Product Page loads successfully without errors. All essential product information is displayed correctly. | Pass | | 
