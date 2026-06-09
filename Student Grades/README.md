# Student Performance Dashboard

An analytical dashboard tracking academic progress, subject averages, top performers, and grade-level performance trends across multiple subjects including Math, Science, English, and History.

## Project Overview

This repository contains data analytics and reporting structures designed for school administrators and educators. It consolidates individual student metrics to identify overall learning gaps, top-performing students, and specific cohorts requiring targeted academic assistance.

---

## Dataset Summary

The primary dataset tracks individual student demographics, enrolled courses, final numeric grades, and corresponding letter grades.

### 1. Subject Analytics
The performance metrics across the core curriculum show highest mastery in English and the greatest area of concern in Science:

| Subject | Average Grade | Total Students |
| :--- | :---: | :---: |
| **English** | 98.00 | 2 |
| **Math** | 85.00 | 4 |
| **History** | 82.50 | 4 |
| **Science** | 62.00 | 2 |

### 2. Honor Roll (Top Performers)
Students achieving a final grade of 90 or above:

*   **Mitchell Morrison** (Math) — 100
*   **Christine Rios** (English) — 98
*   **Amanda Mccoy** (English) — 98
*   **Deborah Sawyer** (History) — 93
*   **Vincent Price** (History) — 91
*   **Nicholas Palmer** (Math) — 91

### 3. Academic Intervention (Needs Improvement)
Students currently tracking below a passing standard who require localized academic support:

*   **Brad Magee** (Math) — 69 (D)
*   **Zachary Jackson** (History) — 64 (D)
*   **Annette Johnson** (Science) — 52 (F)

### 4. Cohort Performance Breakdown
An analysis of student status segmented by grade level highlights that academic risk is highly concentrated in upper-grade cohorts (Grades 11 and 12):

| Grade Level | Passing Count | Needs Improvement Count |
| :---: | :---: | :---: |
| **Grade 9** | 4 | 0 |
| **Grade 10** | 2 | 0 |
| **Grade 11** | 1 | 2 |
| **Grade 12** | 2 | 2 |

---

## Features & Insights

*   **Subject Diagnostics**: Automatically calculates subject averages and groups enrollment densities.
*   **Automated Risk Flags**: Identifies students with D/F letter grades for counseling and remedial tracking.
*   **Cohort Segmentation**: Isolates performance counts by high school grade level to track macro-level academic trends.

## License

This project is open-source and available under the [MIT License](https://opensource.org).
