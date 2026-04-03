# Google Sheets Formulas and Styling Tips for Building Dashboards

## 1. Formula Basics
- **SUM:** `=SUM(A1:A10)` - Sums the values in cells A1 through A10.
- **AVERAGE:** `=AVERAGE(B1:B10)` - Calculates the average of the values in B1 through B10.

## 2. Data Manipulation Formulas
- **IF:** `=IF(C1>100, "Over 100", "Under 100")` - Returns "Over 100" if C1 is greater than 100, otherwise returns "Under 100".
- **VLOOKUP:** `=VLOOKUP(D1, A1:B10, 2, FALSE)` - Looks for the value in D1 within A1:A10 and returns the corresponding value from the second column.

## 3. Date and Time Functions
- **TODAY:** `=TODAY()` - Returns the current date.
- **NOW:** `=NOW()` - Returns the current date and time.

## 4. Formatting Tips
- **Conditional Formatting:** Use this to highlight data that meets specific criteria. For example, highlight cells over a certain value in red.
- **Cell Styles:** Use cell styles to maintain a consistent look across your dashboard.  Make sure to use headers, bold fonts, and adequate alignment.

## 5. Dashboard Design Tips
- **Use Charts:** Use pie charts for contributions, bar graphs for comparisons, and line charts for trends. 
- **Keep It Simple:** Avoid clutter. Only include necessary data and visuals for clarity.
- **Interactive Elements:** Consider using dropdown lists or checkboxes for user interaction.

---

This guide helps you effectively use Google Sheets tools to build and design your dashboard.