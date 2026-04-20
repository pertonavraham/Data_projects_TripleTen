# B2B Revenue & Operational Expense Analysis (June–July 2021)

This repository contains a specialized financial analysis of B2B customer transactions and operational expenses for a service-based business. The project focuses on currency normalization and multi-category data processing to evaluate net profitability over a two-month period.

## Project Overview
The primary objective of this analysis is to transform raw transaction logs into a structured financial model. By applying real-time exchange rates (USD to GBP/EUR) and segmenting data by service type and operation (Income vs. Expense), the project provides a clear view of cash flow and service-specific performance.

## Key Features
*   **Currency Normalization:** Automated conversion of USD subtotals into GBP and EUR using fixed exchange rates (0.89 and 0.92, respectively).
*   **Operational Segmentation:** Categorization of entries into **Income** (e.g., Standard Haircut, Senior Haircut) and **Expenses** (e.g., Scrunchies, Towels, Shampoo).
*   **Time-Series Cleaning:** extraction of month-specific data from raw "Order Date" stamps to allow for month-over-month comparisons (June vs. July).
*   **B2B Focus:** Exclusive analysis of Database A records, specifically filtered for business-to-business customer engagement.

## Tech Stack & Tools
*   **Excel / Data Engineering:** Leveraged for data sanitization, month extraction, and complex financial calculations.
*   **Pivot Table Modeling:** Used to summarize customer counts by state and evaluate total revenue generated per service category.

## Analysis Summary
The data reflects a high-volume service model where **Senior Haircuts ($92.00 / £81.88)** represent the primary revenue drivers. Technical processing in Version 1.1 successfully isolated month-over-month trends, while Version 1.2 introduced geographic tiering to identify which states contribute most to the B2B customer base.
