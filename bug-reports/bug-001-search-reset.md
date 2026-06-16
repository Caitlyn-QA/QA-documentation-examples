# BUG-001 Search Does Not Reset Active Filters
## Summary
Search functionality does not reset active category filters after a search is performed.

## Environment
- Browser: Chrome
- Operating System: Windows 11

## Steps to Reproduce
1. Open the Product Overview page.
2. Select the "Drill" category filter.
3. Enter "pliers" into the Search field.
4. Click Search.

## Expected Result
Search results are displayed and active category filters are reset.

## Actual Result
Search results are displayed, but the selected category filter remains active.

## Severity
Medium

## Priority
Medium

## Reference
Related Test Case: TC-003 Search Resets Active Filters

## Status
New
