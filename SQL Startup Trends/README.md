# Startup & Investment Ecosystem: SQL Data Analysis

This repository contains a series of complex SQL queries designed to extract strategic insights from a relational database modeling the global startup and investment ecosystem. The analysis focuses on funding trends, company statuses, and the educational backgrounds of key industry personnel.

## Project Overview
The primary objective of this project is to leverage relational data to understand the drivers of startup success and investment activity. By querying multiple interconnected tables—including `company`, `acquisition`, `fund`, and `people`—the analysis provides a granular look at market dynamics and institutional behavior.

SQL Formulas: https://docs.google.com/document/d/1Cin02y-sf5MP-YSq53U97BvUH1a79rvCCAA66tnrZPY/edit?tab=t.0
## Key Features
*   **Company Status Tracking:** Automated count of defunct companies to assess market volatility.
*   **Funding Trend Analysis:** Comparative study of total funding amounts across specific countries and categories, such as 'news' in the USA.
*   **Acquisition Modeling:** Calculation of total cash-based acquisition prices within specific multi-year windows (2011–2013).
*   **Institutional Activity Tiering:** Categorization of investment funds into 'high', 'middle', and 'low' activity tiers based on the number of companies in their portfolios.
*   **Educational Correlation:** Advanced subqueries to determine the average number of degrees held by individuals at companies that have closed after a single funding round.
*   **Global Funding Distribution:** Aggregated summary of total funding by country code, ordered to highlight top-performing global markets.

## Tech Stack & Tools
*   **SQL (PostgreSQL/Standard SQL):** The core language used for all data extraction, aggregation, and complex joins.
*   **Relational Database Modeling:** Utilization of primary (PK) and foreign keys (FK) across seven interconnected tables to maintain data integrity.

## Analysis Summary
The analysis reveals critical patterns in the investment lifecycle, from initial funding rounds to final acquisitions. By grouping funds by activity levels and correlating investment rounds with activity tiers, the study identifies a "middle activity" segment as a key driver of consistent investment rounds. Furthermore, the global mapping of `funding_total` provides a clear leaderboard of which international markets are currently attracting the highest concentrations of capital.

