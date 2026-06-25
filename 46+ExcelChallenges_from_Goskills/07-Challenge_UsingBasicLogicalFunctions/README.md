# # Excel Challenge #7: Create an Expandable Dropdown List

# 

# This repository contains my solution to the Excel Challenge #7 from GoSkills. This challenge tests lookup efficiency and data integrity workflows, specifically focusing on creating dynamic data validation boundaries and leveraging modern reference functions.

# 

# ## 📋 Task Overview

# 

# The project simulates a database management request for a corner bookstore. The store owner needs a robust search engine to look up a specific Book ID and automatically extract its entire data record from the inventory catalog.

# 

# ### 🎯 Key Objectives:

# 1. **Dynamic Data Validation:** Create an expandable dropdown list in cell A2 that scales automatically (expands or contracts) as books are added to or removed from the database table.

# 2. **Efficient Row Extraction:** Write a formula in row 5 that references the selected Book ID to pull the complete corresponding data row from the database in a single step.

# 3. **Array Spill Optimization:** Utilize modern lookup behaviors to populate multiple adjacent cell fields automatically from a single formula source entry.

# 

# ---

# 

# ## 🛠️ Data Engineering & Analysis Steps

# 

# * **Dynamic Validation Ranges:** Bound the data validation list directly to an structured Excel Table column or a dynamic array anchor to guarantee list expansion upon database changes.

# * **Modern Array Lookups:** Implemented the `XLOOKUP` function to find the target Book ID and return an entire row array natively using its vertical-to-horizontal spill capabilities.

# * **Input Error Prevention:** Enforced strict dropdown restrictions on the query entry cell to minimize manual transaction input errors for store employees.

# 

# ---

# 

# ## 🏆 FINAL SOLUTION

# 

# ![Excel Challenge 7 Final](./7-Challenge\_img/Final-file-1.png)

# ![Excel Challenge 7 Final](./7-Challenge\_img/Final-file-2.png)





# You can review and download the completed workbook containing the expandable dropdown and dynamic row lookup logic here:

# 

# 👉 [Download excel-challenge-7-FINAL.xlsx](./7-Challenge\_CreateAnExpandableDropdownList/excel-challenge-7-FINAL.xlsx)

