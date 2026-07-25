# Search Test Cases

| ID | Title | Preconditions | Test Data | Steps | Expected Result |
|----|-------|---------------|-------|-------|-----------------|
| SRCH-001 | Search field is displayed | User is on Main page |  | 1. Check if search field is displayed correctly. | Search field is displayed correctly. |
| SRCH-002 | Search using existing product name | User is on Main page | "jacket" | 1. Enter the value from Test Data into the search field.<br /> 2. Click search button.<br />  | Matching products are displayed |
| SRCH-003 | Search non-existing product | User is on Main page | "roof" | 1.  Enter the value from Test Data into the search field.<br /> 2. Click search button.<br />  | "No search performed" message is displayed. |
| SRCH-004 | Search with empty input | User is on Main page | | 1. Leave blank search field.<br /> 2. Click search button<br />  | "No search performed" message is displayed. |
| SRCH-005 | Search using numbers | User is on Main page | 45 | 1. Enter the value from Test Data into the search field.<br /> 2. Click search button.<br /> | Matching products are displayed if found; otherwise, an appropriate "No search performed" message is shown. |
| SRCH-006 | Search using special characters | User is on Main page | "$%^" | 1. Enter the value from Test Data into the search field.<br /> 2. Click search button.<br /> | Matching products are displayed if found; otherwise, an appropriate "No search performed" message is shown. |
| SRCH-007 | Search with spaces only | User is on Main page | " " | 1. Enter the value from Test Data into the search field.<br /> 2. Click search button.<br /> | "No search performed" message is shown. |
| SRCH-008 | Search is case-insensitive | User is on Main page | "JACKET" | 1. Enter the value from Test Data into the search field.<br /> 2. Click search button.<br /> | Matching products are displayed |
| SRCH-009 | Search with very long text | User is on Main page |  | 1. Enter a very long text (e.g., 100 characters) into the search field.<br /> 2. Click search button.<br /> | "No search performed" message is shown. |
| SRCH-010 | Search using mixed letters and numbers | User is on Main page | "a7a8" | 1. Enter the value from Test Data into the search field.<br /> 2. Click search button.<br /> | Matching products are displayed if found; otherwise, an appropriate "No search performed" message is shown. |
| SRCH-011 | Search by pressing Enter | User is on Main page | jacket | 1. Enter the value into the search field.<br /> 2. Press enter button.<br /> | Pressing the Enter key starts the search and produces the same result as clicking the Search button. |
| SRCH-012 | Search by clicking Search button | User is on Main page | "jacket" | 1. Enter the value from Test Data into the search field.<br /> 2. Click search button.<br /> | Matching products are displayed |
| SRCH-013 | Clear search input | User is on Main page | "jacket" | 1. Enter the value from Test Data into the search field.<br /> Remove the entered text using the Backspace key.<br /> | The search field becomes empty. |
