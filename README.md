# Excel Data Exploratiom assignment 

## Overview of Tasks Completed
1. **Sum, Count, Average:** Calculated the total price, total count, and average price of all products in the dataset.
2. **Min and Max:** Determined the minimum and maximum prices across all products.
3. **IF Function:** Created a 'Price Range' column using an IF statement to categorize products with a price >= 500 as 'High Price' and others as 'Standard Price'.
4. **SUMIF and COUNTIF:** Computed the total price for products in the 'Electronics' category using SUMIF, and counted products priced below 100 using COUNTIF.
5. **Text Formatting (LEFT, RIGHT, MID):** 
   - Extracted the first 2 characters for the 'Day' column using the LEFT function.
   - Extracted the last 2 characters for the 'Country Code' column using the RIGHT function.
   - Extracted the 4th to 6th characters for the 'Month' column using the MID function.

## Revision & Bug Fixes
- **Problem:** In the initial submission, the MID function for the 'Month' column inadvertently captured extra characters (including hyphens and country codes).
- **Solution:** Corrected the formula to `=MID(A2, 4, 3)` to accurately isolate only the 3-letter month abbreviation. All requirements have now been fully tested and validated.
