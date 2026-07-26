# Homepage Execution

| Test Case | Actual Result                                                                       | Status | Bug        |
| --------- | ----------------------------------------------------------------------------------- | ------ | ---------- |
| SRCH-001  | Existing products matching the search query were displayed correctly.               | Pass | |
| SRCH-002  | "No results found" message was displayed correctly.                                 | Pass |
| SRCH-003  | Empty search returned all products.                                                 | Pass |
| SRCH-004  | Search was executed successfully using the Enter key.                               | Pass |
| SRCH-005  | Numeric search returned no matching products and displayed the appropriate message. | Pass |

| HOME-001 | The Home page loads successfully without errors. All page elements are displayed correctly. | Pass |
| HOME-002 | The website logo is visible, properly rendered, and displayed without visual defects. | 
| HOME-003 | User is redirected to the Home page successfully. | 
| HOME-004 | The navigation menu is visible and all menu items are displayed correctly. | 
| HOME-005 | The Featured Products section is visible and displayed correctly. | 
| HOME-006 | Product cards are displayed correctly with all required information and without layout issues. | 
| HOME-007 | The footer is displayed correctly and all footer elements are visible. | 
| HOME-008 | Contact information is visible, readable, and properly formatted. | 
| HOME-009 | All available social media icons or links are displayed correctly. | 
| HOME-010 | All links work except share link | Fail | BUG-001 |
| HOME-011 | All images are displayed correctly without distortion or missing content. | 
| HOME-012 | No broken image icons, placeholders, or image loading errors are present. | 
| HOME-013 | Every link redirects to the expected destination without errors | 
| HOME-014 | All page elements are aligned correctly. No overlapping, clipping, or layout issues are present. | 
| HOME-015 | The Home page reloads successfully. All elements remain functional and are displayed correctly after the refresh. | 
| HOME-016 | The browser title is displayed correctly and matches the expected page title. | 
| HOME-017 | The website favicon is displayed correctly in the browser tab without visual defects. | 
| HOME-018 | The page URL is correct, valid, and corresponds to the Home page. | 
| HOME-019 | No unnecessary horizontal scrollbar is displayed. The page content fits within the browser viewport. | 
| HOME-020 | Verify Home page is displayed correctly after browser resize | User is on the Home page | 1. Open the Home page.<br> 2. Resize the browser window to different widths.<br> 3. Observe the page layout. | The Home page layout adjusts correctly without overlapping elements, broken layouts, or missing content. | 
| HOME-021 | Verify keyboard navigation on the Home page | User is on the Home page | 1. Press the Tab key repeatedly.<br> 2. Navigate through interactive elements.<br> 3. Press Enter on a selected element. | Keyboard focus moves logically between interactive elements. The focused element is clearly visible, and pressing Enter activates it correctly. | 
| HOME-022 | Verify all clickable elements respond correctly | User is on the Home page | 1. Click each clickable element on the Home page. | Every clickable element performs its expected action. No inactive or unresponsive elements are present. | 
