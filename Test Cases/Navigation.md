# Navigation Test Cases

| ID | Title | Preconditions | Steps | Expected Result |
|----|-------|---------------|-------|-----------------|
| NAV-001 | Verify navigation menu is displayed | User is on the Home page | 1. Open the Home page.<br> 2. Observe the page header. | The navigation menu is visible, properly aligned, and all menu items are displayed correctly. | 
| NAV-002 | Verify logo redirects to the Home page | User is on any page other than the Home page | 1. Click the website logo. | The user is redirected to the Home page successfully. | 
| NAV-003 | Verify every navigation item opens the correct page | User is on the Home page | 1. Click each navigation menu item one by one.<br> 2. Verify the opened page. | Each navigation item opens the corresponding page without errors. | 
| NAV-004 | Verify the active navigation item is highlighted | User is on any page accessible through the navigation menu | 1. Open a page using the navigation menu.<br> 2. Observe the selected menu item. | The active navigation item is visually highlighted, indicating the current page. | 
| NAV-005 | Verify hover effect works correctly | User is on the Home page | 1. Move the mouse pointer over each navigation menu item. | The hover effect is displayed correctly for every navigation item without visual issues. | 
| NAV-006 | Verify Browser Back button works correctly | User has navigated between at least two pages | 1. Open a second page using the navigation menu.<br> 2. Click the browser Back button. | The browser returns to the previous page successfully and the page content is displayed correctly. | 
| NAV-007 | Verify Browser Forward button works correctly | User has used the browser Back button | 1. Click the browser Forward button. | The browser returns to the next page successfully and the page content is displayed correctly. | 
| NAV-008 | Verify navigation works after page refresh | User is on any page | 1. Refresh the current page.<br> 2. Click a navigation menu item. | Navigation continues to work correctly after the page refresh. | 
| NAV-009 | Verify navigation links are not broken | User is on the Home page | 1. Open each navigation link.<br> 2. Verify that each destination page loads successfully. | Every navigation link opens the expected page. No broken links. | 
