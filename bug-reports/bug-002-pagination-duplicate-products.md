#BUG-002 Pagination Displays Duplicate Products

## Summary
Pagination displays products from a previous page instead of showing a unique set of products for the selected page.

## Environment
- Browser: Chrome
- Operating System: Windows 11

## Steps to Reproduce
1. Open the Product Overview page.
2. Note the products displayed on page 1.
3. Click page 2 in the pagination controls.
4. Compare the displayed products with those from page 1.

## Expected Result
Page 2 displays a different set of products from page 1.

## Actual Result
One or more products from page 1 are displayed again on page 2.

## Severity
Medium

## Priority
Medium

## Reference
Related Test Case: TC-008 Navigate to Another Page

## Status
New
