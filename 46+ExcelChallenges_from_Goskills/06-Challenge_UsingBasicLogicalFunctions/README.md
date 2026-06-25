# # Excel Challenge #6: Using Basic Logical Functions

# 

# This repository contains my solution to the Excel Challenge #6 from GoSkills.This challenge focuses on applying conditional logic and statistical criteria aggregation using native spreadsheet functions to solve an HR priority routing workflow.

# 

# ## 📋 Task Overview

# 

# ![Excel Challenge 6 Task](./6-Challenge\_img/Task-file-1.png)

# 

# The project simulates a year-end Human Resources operational scenario where employees are rushing to claim remaining vacation days. The HR Department requires an automated matrix to prioritize vacation approvals based on employee tenure and remaining leave balances.

# 

# ### 🎯 Key Objectives:

# 1. **Priority Evaluation:** Write a logical formula in column E to mark an employee as "Priority" if they have more than 5 vacation days remaining OR if their company tenure is 3 years or more.

# 2. **Blank State Formatting:** Ensure that if neither condition is met, the cell remains entirely blank.

# 3. **Departmental Criteria Querying:** Build an analytical lookup formula in cell B17 that dynamically aggregates total remaining vacation days based on a department selected from a B16 drop-down list.

# 

# ---

# 

# ## 🛠️ Data Engineering & Analysis Steps

# 

# * **Nested Logical Arguments:** Implemented a combination of `IF` and `OR` functions to construct a multi-conditional evaluation layer for the request status routing.

# * **Conditional Criteria Aggregation:** Leveraged the `SUMIF` function to dynamically sum remaining vacation balances matching variable department filter states.

# * **Interface Alignment:** Integrated data collection boundaries using the cell B16 data validation list to trigger responsive updates in the dashboard calculations.

# 

# ---

# 

# ## 🏆 FINAL SOLUTION

# 

# ![Excel Challenge 6 Final](./6-Challenge\_img/Final-file-1.png)

# 

# You can review and download the completed workbook containing the conditional evaluation logic and departmental summaries here:

# 

# 👉 [Download excel-challenge-6-FINAL.xlsx](./6-Challenge\_UsingBasicLogicalFunctions/excel-challenge-6-FINAL.xlsx)

