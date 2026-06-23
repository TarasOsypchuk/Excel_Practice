# Excel Challenge #1: Use Raw Data to Create Dynamic Reports

This repository contains my solution to the Excel Challenge #1 from GoSkills. The purpose of this challenge is to demonstrate the ability to work with formulas, text manipulation, data aggregation, and dynamic charting in Microsoft Excel.

## 📋 Task Overview

The challenge provides a dataset containing sales records with unique transaction references, dates, and amounts. The objectives are as follows:

1. **Extract Region Codes:** Write a dynamic formula to extract the three-digit region code from the middle of the text string in the `Ref` column (e.g., extracting `GBR` from `1044-GBR-11`).
2. **Sales Analysis:**
   - Calculate the total sales for each specific region (`DEU`, `FRA`, `GBR`, `NZL`).
   - Calculate the number of transactions that met or exceeded a predefined target value of `2,500`.
3. **Dynamic Solution:** Ensure that all formulas automatically scale and update when new data rows are added to the table.
4. **Data Visualization:** Create a clean, visually appealing, and easy-to-understand column chart representing the *Total Sales by Region*.

---

## 🛠️ Approach & Functions Used

- **Text Manipulation:** Used text functions to cleanly parse and isolate the region codes from the variable-length reference strings.
- **Conditional Summing & Counting:** Utilized `SUMIF` / `SUMIFS` for aggregating sales by region and `COUNTIF` / `COUNTIFS` to evaluate performance against the sales target.
- **Dynamic Excel Tables:** Converted raw data ranges into official Excel Tables to ensure automatic formula expansion and dynamic chart updates upon inserting new test data.

---

## 🏆 FINAL SOLUTION

You can review and download the completed spreadsheet with all dynamic formulas and the column chart here:

👉 [Download excel-challenge-1-FINAL.xlsx](./1-Challenge_UserRawDataToCreateDynamicReports/excel-challenge-1-FINAL.xlsx)

*(Note: If you have a different folder structure on GitHub, make sure to adjust the relative link path above so it points directly to your file).*