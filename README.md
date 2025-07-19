# Sales-Performance-Dashboard--Power-BI
A Power BI project that visualizes and compares sales performance between the years 2023 and 2024 across different metrics, regions, and product categories. 

## Table of Contents
- [Project Overview](#project-Overview)
- [Objectives](#objectives)
- [Goal](#goal)
- [Dataset Overview](#dataset-overview)
- [ Data Preparation](#data-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)


## Project Overview


## Objectives
The objective of this analysis is to evaluate and enhance sales performance by identifying key trends and patterns across multiple business metrics. Using an interactive Power BI dashboard, the project addresses the following business questions:

1. **How have key performance indicators (Sales, Quantity, Profit, and Cost) evolved between 2023 and 2024?**
2. **What is the year-over-year (YoY) growth or decline across these KPIs, and how can it inform decision-making?**
3. **Which months are driving the most revenue, and are there specific time periods where performance dips or spikes?**
4. **Which product categories are contributing most to overall sales, and are there any underperforming categories that require attention?**
5. **Which region is generating the highest sales, and how does performance vary across regions?**
6. **How is revenue trending on a monthly basis, and are we building consistent momentum throughout the year or experiencing volatility?**

## Goal
The goal of this project is to develop a dynamic and insightful Power BI dashboard that monitors, evaluates, and compares sales performance across different time periods, regions, and product categories. By transforming raw sales data into actionable insights, the dashboard aims to support data-driven decision-making, identify growth opportunities, and highlight areas requiring strategic focus.

## Dataset Overview
- Extracted Month and Year columns from the original Date field for filtering and comparison. (Month was formatted as 3-letter abbreviations for readability.)
- Generated a Quarter column in Power Query based on the Date field. Created a Quarter Number column (1 to 4) and sorted it to maintain correct chronological order in visuals.
- Verified there were no missing values or duplicate records present in the dataset.
- Ensured all columns (e.g., Date, Sales, Quantity, Profit, Cost) were assigned appropriate data types.
- Created DAX measures for key metrics including:
  - Total Sales, Profit, Quantity, and Cost.
  - Year-over-Year (YoY) comparisons between 2023 and 2024.
  - YoY Growth (%) and dynamic visual indicators for performance trends.



