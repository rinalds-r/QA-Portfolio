# Bug Reports Summary

| ID | Title | Module | Severity | Priority | Preconditions | Steps | Expected Result | Actual Result | Status |
|----|-------|------------|----------|----------|----------|----------|----------|----------|--------|
| BUG-001 | Wishlist link does not navigate to the expected page | Homepage / Navigation | Medium | Medium | User is on the Home page | 1. Open the Home page.<br> 2. Click the Wishlist link. | The user is redirected to the Wishlist page. | Clicking the Wishlist link does not redirect the user to any page. | Open |
| BUG-002 | Refer a Friend link does not navigate to the expected page | Homepage / Navigation | Medium | Low | User is on the Home page | 1. Open the Home page.<br> 2. Click Refer a Friend link. | The user is redirected to Refer a Friend page. | Clicking the Refer a Friend link does not redirect the user to any page. | Open |
| BUG-003 | Active navigation item is not highlighted correctly | Homepage / Navigation | Medium | Low | User is on the Home page | 1. Open the Home page.<br> 2. Click any working navigation item.<br> 3. Click Wishlist or Refer a Friend. | The navigation item corresponding to the currently opened page is highlighted. Inactive or unavailable pages are not highlighted. | Working navigation items are not highlighted after navigation. Instead, non-functional menu items (Wishlist or Refer a Friend) are highlighted. | Open |
| BUG-004 | Cart page loads indefinitely after adding a product to cart | Homepage / Navigation | High | High | User is on a Product Page. | 1. Open any Product Page.<br> 2. Click the "Add to Cart" button.<br> 3. Open Cart. | The selected product is added to the cart successfully. The Shopping Cart page loads correctly and displays the added product. | After clicking the "Add to Cart" button, and open Cart, the Shopping Cart page enters an infinite loading state. After page reload Cart loaded and added products displayed. | Open |

Attachments:
BUG-004-cart-loading.png
