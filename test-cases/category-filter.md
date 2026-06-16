# Category Filter Test Cases

## TC-004 Filter by Category
### Precondition
User is on the Product Overview page.

### Steps
1. Select a category filter.
2. Observe the updated product list.

### Expected Result
Only products belonging to the selected category are displayed.

## TC-005 Multiple Category Selection
### Precondition
User is on the Product Overview page.

### Steps
1. Select a category filter.
2. Select a second category filter.
3. Observe the displayed products.

### Expected Result
Products belonging to either of the selected categories are displayed.

## TC-006 Unchecking Category Restores Products
### Precondition
User is on the Product Overview page.
A category filter is selected.

### Steps
1. Select a category filter.
2. Observe the filtered product list.
3. Uncheck the selected category filter.

### Expected Result
The product list returns to its previous unfiltered state.
