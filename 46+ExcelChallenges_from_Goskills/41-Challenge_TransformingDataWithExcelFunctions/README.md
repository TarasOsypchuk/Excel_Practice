# \# Excel Challenge #20: Calculate Years Between Two Dates

# 

# This repository contains my solution to the Excel Challenge #20 from GoSkills. This challenge focuses on temporal data calculations, exact date interval processing, conditional eligibility routing, and customized multidimensional sorting rules within HR employee databases.

# 

# \## 📋 Task Overview

# 

# !\[Excel Challenge 20 Task](./20-Challenge\_img/Task-file-1.png)

# !\[Excel Challenge 20 Task](./20-Challenge\_img/Task-file-2.png)

# 

# The project handles an HR operational dataset tracking employee metrics, including specific hire dates, role titles, and retirement program eligibility. The company's policy states that employees who accumulate 10 or more complete years of tenure with the organization on the September 30 cut-off target will be considered "vested" for an extra pension benefit.

# 

# \### 🎯 Key Objectives:

# 1\. \*\*Tenure Calculations:\*\* Compute the precise number of complete operational years between each employee's hire date and the target cut-off deadline.

# 2\. \*\*Conditional Vesting Authorization:\*\* Write an evaluation formula in Column E to dynamically return a "Vested" string marker only for employees who satisfy the 10-year tenure threshold.

# 3\. \*\*Custom Sequence Sorting:\*\* Restructure the ledger order by job title to enforce a non-alphabetical corporate ranking sequence: `Associates` first, followed by `Team Leads`, and concluding with `Senior Managers`.

# 4\. \*\*Targeted Data Filtration:\*\* Filter the final processed data grid to exclusively display the subset of employees who qualify as vested.

# 

# \---

# 

# \## 🛠️ Data Engineering \& Analysis Steps

# 

# \* \*\*Temporal Interval Compiling:\*\* Deployed exact date delta functions (such as `DATEDIF` using the `"Y"` parameter or precise calendar threshold evaluation models) to capture complete elapsed years while dropping partial months.

# \* \*\*Logic Qualification Filters:\*\* Built conditional verification strings using logical `IF` statements to isolate records where tenure meets or exceeds the 10-year baseline.

# \* \*\*Custom List Priority Sorts:\*\* Applied custom array sorting profiles to arrange corporate roles into the required organizational hierarchy (`Associate` > `Team Lead` > `Senior Manager`) instead of default character patterns.

# \* \*\*Record Subset Extraction:\*\* Configured dataset row visibility rules to suppress non-eligible records and isolate the key vested workforce segment for stakeholders.

# 

# \---

# 

# \## 🏆 FINAL SOLUTION

# 

# !\[Excel Challenge 20 Final](./20-Challenge\_img/Final-file-1.png)

# 

# You can review and download the completed workbook containing the employee tenure calculator, custom-sorted roster, and filtered vesting dashboard here:

# 

# 👉 \[Download excel-challenge-20-FINAL.xlsx](./20-Challenge\_CalculateYearsBetweenTwoDates/excel-challenge-20-FINAL.xlsx)

