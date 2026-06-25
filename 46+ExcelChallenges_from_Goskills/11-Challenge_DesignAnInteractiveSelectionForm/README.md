# \# Excel Challenge #11: Design an Interactive Selection Form

# 

# This repository contains my solution to the Excel Challenge #11 from GoSkills. This challenge focuses on user-interface design within spreadsheets, data validation configuration, and relational search queries to enforce complex selection business rules and minimize operational input errors.

# 

# \## 📋 Task Overview

# 

# The project handles an academic course selection model containing four primary Pathways: Arts, Business, Science, and Technology, each hosting seven specific subjects. Students must select a total of seven subjects, ensuring exactly four subjects are taken from their primary chosen Pathway, while the remaining three can be selected from any program area.

# 

# \### 🎯 Key Objectives:

# 1\. \*\*Interactive Form Architecture:\*\* Design an automated Course Selection form on the second worksheet that dynamically restricts user selections to eliminate rule-breaking entries.

# 2\. \*\*Dependent Validation Controls:\*\* Configure strict conditional boundaries to prevent selection errors and enforce the specific 4-pathway / 3-elective balancing rules.

# 3\. \*\*Student Selection Query Engine:\*\* Design an administrative lookup dashboard on the Student Selections data matrix to allow school administrators to query complete individual student course paths instantly by entering a student's name.

# 4\. \*\*Data Integrity Optimization:\*\* Implement duplicate removal processes and clean lookup workflows to establish an error-proof user interface.

# 

# \---

# 

# \## 🛠️ Data Engineering \& Analysis Steps

# 

# \* \*\*Dependent Data Validation:\*\* Leveraged advanced data validation parameters and named range rules to build contextual dropdown fields that adapt to user pathways.

# \* \*\*Array-Based Querying:\*\* Deployed modern lookup functions (`XLOOKUP` / `VLOOKUP`) to map single string name parameters against multi-column horizontal arrays for data extraction.

# \* \*\*Operational Rule Enforcement:\*\* Programmed background calculation cells to audit criteria volume thresholds, flagging compliance and blocks directly on the user input layer.

# \* \*\*Duplicate Scrubbing:\*\* Structured cleaner data boundaries by identifying and isolating unique key identifiers to populate core selection indexes.

# 

# \---

# 

# \## 🏆 FINAL SOLUTION

# 

# 

# You can review and download the completed workbook containing the interactive course selection interface and administrative query system here:

# 

# 👉 \[Download excel-challenge-11-FINAL.xlsx](./11-Challenge\_DesignAnInteractiveSelectionForm/excel-challenge-11-FINAL.xlsx)

