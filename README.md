# CC_lab3

Optimizations Summary
1. cart :
Replaced nested loops with list comprehension in get_cart for better efficiency.

2. checkout:
Simplified total cost calculation by replacing the while loop with sum(item.cost for item in cart).
Removed unsafe os._exit(1) to prevent abrupt process termination.

3. products:
Used list comprehension in list_products, eliminating redundant loops for better readability and performance.

4. browse:
Removed redundant headers (Host, Priority).
Used self.default_headers to avoid duplication in requests.
Renamed class to BrowseUser (PascalCase for readability).
Renamed task method to browse_page for clarity.

Overall: Improved performance, readability, and maintainability across all files.
