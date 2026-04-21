# Zomato Consumer Retention & Behavior Analysis

This repository contains a comprehensive Consumer Behavior Analysis for the Zomato platform, developed using Tableau. The project explores the demographic and socioeconomic drivers of food ordering habits to help focus marketing strategies toward high-value user segments.

## Project Overview
The primary goal of this analysis is to identify which consumer segments eat out most frequently and spend the most on the platform. By testing several hypotheses related to age, occupation, and family size, the project identifies key target personas for advertising focus.

Tableau Public Link: https://public.tableau.com/views/ZomatoConsumerRetentionBehaviorAnalysis/DashboardPresentation?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
## Key Features
*   **Demographic Segmentation:** Detailed analysis of users by **Gender, Age Group (18-34), and Education Level** (Graduate, Post Graduate, Ph.D.).
*   **Socioeconomic Profiling:** Evaluation of spending habits based on **Monthly Income** (e.g., No Income, 25k-50k, 50k+) and **Occupation** (Student, Employee, Self-Employed, Housewife).
*   **Family Dynamics Modeling:** A "Family Size Calculation" that cross-references household size (Small, Medium, Large) with **Average Order Value (AOV)** and total spend.
*   **Behavioral Hypothesis Testing:** Research-driven visualizations that answer questions such as whether students order more frequently or if higher income correlates with higher spend.

## Tech Stack & Tools
*   **Tableau:** Used for end-to-end data visualization, composite charting, and interactive dashboarding.
*   **Data Engineering:** Implementation of left joins between `users.csv` and `orders.csv` using `user_ID`.
*   **Analytics:** Application of machine learning for preliminary user clustering and qualitative research on user archetypes.

## Analysis Summary
The data indicates that consumers vary more by their **stage of life** than by income alone. While students and young professionals (ages 22-24) represent a high volume of orders, family size remains a critical factor in determining total sales amount. The analysis successfully mapped over **986 million in sales** across 2.4 million quantity units, providing a data-driven roadmap for Zomato’s future retention efforts.
