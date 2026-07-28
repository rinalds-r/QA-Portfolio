# Bug Reports Summary

| ID | Title | Module | Severity | Priority | Status |
|----|-------|--------|----------|----------|--------|
| BUG-001 | Wishlist link does not navigate to the expected page | Homepage / Navigation | Medium | Medium | Open |
| BUG-002 | Refer a Friend link does not navigate to the expected page | Homepage / Navigation | Medium | Low | Open |
| BUG-003 | Active navigation item is not highlighted correctly | Homepage / Navigation | Low | Low | Open |
| BUG-004 | Cart page loads indefinitely after adding a product to cart | Product Page / Shopping Cart | High | High | Open |


---

# BUG-001 - Wishlist link does not navigate to the expected page

## Module
Homepage / Navigation

## Severity
Medium

## Priority
Medium

## Environment
- Windows 10
- Google Chrome 150

## Preconditions
User is on the Home page.

## Steps to Reproduce
1. Open the Home page.
2. Locate the Wishlist link.
3. Click the Wishlist link.

## Expected Result
The user is redirected to the Wishlist page.

## Actual Result
Clicking the Wishlist link does not redirect the user to any page.


---

# BUG-002 - Refer a Friend link does not navigate to the expected page

## Module
Homepage / Navigation

## Severity
Medium

## Priority
Low

## Environment
- Windows 10
- Google Chrome 150

## Preconditions
User is on the Home page.

## Steps to Reproduce
1. Open the Home page.
2. Locate the Refer a Friend link.
3. Click the Refer a Friend link.

## Expected Result
The user is redirected to the Refer a Friend page.

## Actual Result
Clicking the Refer a Friend link does not redirect the user to any page.


---

# BUG-003 - Active navigation item is not highlighted correctly

## Module
Homepage / Navigation

## Severity
Low

## Priority
Low

## Environment
- Windows 10
- Google Chrome 150

## Preconditions
User is on the Home page.

## Steps to Reproduce
1. Open the Home page.
2. Click any working navigation item.
3. Click Wishlist or Refer a Friend.

## Expected Result
The navigation item corresponding to the currently opened page is highlighted. Inactive or unavailable pages are not highlighted.

## Actual Result
Working navigation items are not highlighted after navigation. Instead, non-functional menu items (Wishlist or Refer a Friend) are highlighted.


---

# BUG-004 - Cart page loads indefinitely after adding a product to cart

## Module
Product Page / Shopping Cart

## Severity
High

## Priority
High

## Environment
- Windows 10
- Google Chrome 150

## Preconditions
User is on a Product Page.

## Steps to Reproduce
1. Open any Product Page.
2. Click the "Add to Cart" button.
3. Open Cart.

## Expected Result
The selected product is added to the cart successfully. The Shopping Cart page loads correctly and displays the added product.

## Actual Result
After clicking the "Add to Cart" button and opening the Cart page, the Shopping Cart enters an infinite loading state.

## Attachments
BUG-004-cart-loading.png
