# Excel Challenge #34: Assign Random Values

This repository contains my solution to the Excel Challenge #41 from GoSkills. This challenge focuses on algorithmic data transformations, dynamic time-based extrapolations, deduplicated tracking index generation, dynamic multi-key table sorting, and distributing uniform cohorts using advanced array reshaping operations.

## 📋 Task Overview

![Excel Challenge 41 Task](./41-Challenge_img/Task-file-1.png)

The project handles logistical sports data engineering for the London Marathon. The operational goal is to programmatically prepare an unorganized athlete dataset, project running timelines, assign secure identification tags, and uniformly segregate the final roster into three balanced starting groups (Blue, Red, and Green waves). The fastest athletes must be routed to the initial Blue wave, while the slowest competitors fill the terminal Green wave.

### 🎯 Key Objectives:
1. **Dynamic Completion Time Estimation (Step 1):** Calculate each athlete's estimated marathon finishing time based on their logged baseline 10-kilometer split time, enforcing a standard `h:mm` timestamp formatting scale.
2. **Deduplicated Identification Tagging (Step 2):** Synthesize random, unique tracking bib numbers restricted between the parameters of `10000` and `99999`, safely removing backend volatile components once populated.
3. **Structured Entity Packaging (Step 3):** Pack the processed rows into a standard relational Excel Table object initialized under the name `Marathon2025`.
4. **Multi-Column Positional Sorting (Step 4):** Isolate and extract an array consisting specifically of the `Athlete`, `Bib Number`, and `Marathon Time` properties. Sort the resulting matrix primarily by estimated marathon speed (fastest to slowest) and secondarily by runner name strings alphabetically.
5. **Global Roster Aggregation (Step 5):** Calculate the exact volume of registered runners inside summary container cell C38.
6. **Uniform Cohort Distribution (Step 6):** Partition the sorted, speed-ordered athlete array evenly across three distinct horizontal wave blocks, automating starting line management.

---

## 🛠️ Data Engineering & Operational Steps

* **Proportional Timeline Extrapolation:** Engineered a localized time multiplication model, extending the raw 10K metrics to match the standard 42-kilometer marathon map boundary distance using precise scaling coefficients (`= [@[10K Time]] * (42 / 10)`).
* **Non-Repeating Numeric Synthesis:** Shuffled a discrete sequential array using standard random generation bounds (`SORTBY(SEQUENCE(90000, 1, 10000), RANDARRAY(90000))`) and extracted values to eliminate the possibility of matching duplicate bib outputs, freezing row variables to values thereafter.
* **Granular Matrix Query Slicing:** Utilized advanced dynamic array functions like `CHOOSECOLS` paired with `SORT` to target exact field indexes, pushing sorted ascending array flags across time matrices followed by alphabetical text criteria.
* **Dynamic Metric Summation:** Deployed standard categorical counting tools like `COUNTA` in cell C38 to continuously compute the absolute row size of active runners.
* **Balanced Cluster Apportionment:** Integrated modern multi-column cell splitting operations (such as combining row-size computations with `WRAPROWS` or positional segment matrices) to evenly divide the sorted, elite-to-slowest athlete blocks into parallel starting columns.

---

## 🏆 FINAL SOLUTION

![Excel Challenge 41 Final](./41-Challenge_img/Final-file-1.png)