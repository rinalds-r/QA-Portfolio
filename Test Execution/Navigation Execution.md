# Navigation Execution

| Test Case | Actual Result                                                                       | Status | Bug        |
| --------- | ----------------------------------------------------------------------------------- | ------ | ---------- |
| NAV-001 | The navigation menu is visible, properly aligned, and all menu items are displayed correctly. | Pass | |
| NAV-002 | The user is redirected to the Home page successfully. | Pass | |
| NAV-003 | The Wishlist link does not respond when clicked. The Refer a Friend link does not respond when clicked. All other clickable elements work as expected. | Fail	| BUG-001, BUG-002 |
| NAV-004 | Navigation highlights inactive menu items instead of the current page | Fail | BUG-003 |
| NAV-005 | The hover effect is displayed correctly for every navigation item without visual issues. | Pass | |
| NAV-006 | The browser returns to the previous page successfully and the page content is displayed correctly. | Pass | |
| NAV-007 | The browser returns to the next page successfully and the page content is displayed correctly. | Pass | |
| NAV-008 | Navigation continues to work correctly after the page refresh. | Pass | |
| NAV-009 | The Wishlist link does not respond when clicked. The Refer a Friend link does not respond when clicked. Other navigation link opens the expected page, with no broken links. | Fail	| BUG-001, BUG-002 |
