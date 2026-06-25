# \# Excel Challenge #12: Methods for Splitting Cell Values

# 

# This repository contains my solution to the Excel Challenge #12 from GoSkills. This challenge focuses on string parsing methodologies, text-to-column transformations, and multi-layered relational sorting structures within analytical datasets.

# 

# \## 📋 Task Overview

# 

# !\[Excel Challenge 12 Task](./12-Challenge\_img/Task-file-1.png)

# The project handles a global demographics dataset containing the top 20 most populated cities in the world. The raw import stores the city name and its corresponding two-letter country code merged within a single data column, which restricts localized sorting and sub-level analysis.

# 

# \### 🎯 Key Objectives:

# 1\. \*\*String Manipulation \& Splitting:\*\* Parse and split the combined city and country text field to isolate them cleanly into two separate, dedicated attributes.

# 2\. \*\*Primary Level Sorting:\*\* Sort the entire processed dataset alphabetically using the newly isolated two-letter country codes.

# 3\. \*\*Secondary Tier Logic Sorting:\*\* Configure a secondary sorting condition where any duplicate country entries are internally ordered alphabetically by their specific city names.

# 4\. \*\*Efficiency Evaluation:\*\* Explore and deploy the most direct and repeatable approach among multiple possible execution methods.

# 

# \---

# 

# \## 🛠️ Data Engineering \& Analysis Steps

# 

# \* \*\*Text Cleansing Pipelines:\*\* Evaluated various structural string methods (such as Text to Columns, Flash Fill, or native `TEXTSPLIT`/`LEFT`/`RIGHT` formulas) to cleanly extract geographical properties.

# \* \*\*Hierarchical Sorting Indexes:\*\* Utilized advanced multi-level sorting rules within Excel's data processing module to establish `Country` as the primary index and `City` as the secondary condition.

# \* \*\*Database Normalization:\*\* Standardized column attributes and removed text-wrap anomalies to prepare raw unorganized records for standalone relational operations.

# 

# \---

# 

# \## 🏆 FINAL SOLUTION

# 

# 

# You can review and download the completed workbook containing the separated attributes and multi-level country-city database order here:

# 

# 👉 \[Download excel-challenge-12-FINAL.xlsx](./12-Challenge\_MethodsForSplittingCellValues/excel-challenge-12-FINAL.xlsx)

