# Search Test Cases

## TC-001 Search Existing Product

### Precondition
User is on the Product Overview page.

### Steps
1. Enter "pliers" into the Search field.
2. Click Search.

### Expected Result
Products matching "pliers" are displayed.

---

## TC-002 Search Non-Existing Product

### Precondition
User is on the Product Overview page.

### Steps
1. Enter "xyz123" into the Search field.
2. Click Search.

### Expected Result
No matching products are displayed.

---

## TC-003 Search Resets Active Filters

### Precondition
User is on the Product Overview page.
A category filter is selected.

### Steps
1. Select a category.
2. Enter a valid search term.
3. Click Search.

### Expected Result
Search results matching the entered search term are displayed.
Previously selected category filters are reset.
