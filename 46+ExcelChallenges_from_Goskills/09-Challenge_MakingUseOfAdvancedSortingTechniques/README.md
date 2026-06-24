# \# Excel Challenge #9: Making Use of Advanced Sorting Techniques

# 

# This repository contains my solution to the Excel Challenge #9 from GoSkills. This challenge focuses on structural multi-level data hierarchy layout manipulation, custom sorting orders, and percentage metric tracking.

# 

# \## 📋 Task Overview

# 

# !\[Excel Challenge 9 Task](./9-Challenge\_img/Task-file-1.png)

# 

# The project presents a dataset from a school board tracking district education entities from elementary to post-secondary levels, including city/town properties and raw population metrics. The initial layout was sorted strictly by school names, which prevents proper regional summary calculations.

# 

# \### 🎯 Key Objectives:

# 1\. \*\*Multi-Tier Regional Sorting:\*\* Sort the dataset alphabetically by town attributes as the primary category layer.

# 2\. \*\*Custom Ordered Sequences:\*\* Within each localized town cluster, structure the secondary school classification level specifically to match a custom administrative ranking rule: `Elementary` > `Middle` > `High` > `Community College` > `University`.

# 3\. \*\*Sub-Level Population Priority:\*\* For instances where towns host multiple entries of identical school types, isolate and sort them progressively starting with the largest population size.

# 4\. \*\*Occupancy Metric Calculations:\*\* Build a column calculation model to the right of the primary table grid to determine the occupancy percentages by comparing population values against fixed structural capacity limits.

# 

# \---

# 

# \## 🛠️ Data Engineering \& Analysis Steps

# 

# \* \*\*Custom List Construction:\*\* Configured a native customized sorting list array inside Excel to override default alphabetical patterns for text strings (`Elementary`, `Middle`, `High`, etc.).

# \* \*\*Advanced Multi-Level Sorts:\*\* Applied sequential data collection rules using the `Sort` window dialog parameters to isolate `Town` (A to Z), `Type` (Custom List), and `Population` (Largest to Smallest).

# \* \*\*Ratio Calculations:\*\* Programmed custom evaluation fields to compute operational capacities ($Population / Capacity$) using appropriate numerical percentage formatting rules.

# 

# \---

# 

# \## 🏆 FINAL SOLUTION

# 

# !\[Excel Challenge 9 Final](./9-Challenge\_img/Final-file-1.png)

# 

# You can review and download the completed workbook containing the multi-tier custom sorted table matrix and capacity calculations here:

# 

# 👉 \[Download excel-challenge-9-FINAL.xlsx](./9-Challenge\_MakingUseOfAdvancedSortingTechniques/excel-challenge-9-FINAL.xlsx)

