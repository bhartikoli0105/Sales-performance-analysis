Swiggy Food Data Analysis & Excel Dashboard
An Excel-based data analytics project exploring Swiggy restaurant and food-item data across Indian cities and states. The workbook summarizes price values, customer ratings, rating counts, food type, restaurant/category performance, and time-based patterns.
Project type: Portfolio / practice project
Tool: Microsoft Excel
Dataset period: 1 January 2025 – 31 August 2025
Records: 197,430
Currency: Indian Rupees (INR)

Table of Contents
- Project Overview
- Business Objectives
- Dataset Description
- Key Metrics in the Workbook
- Analysis Included
- Tools and Excel Skills
- How to Use the Project
- Key Findings
- Important Data Notes
- Repository Structure
- Future Improvements
Project Overview
The objective of this project is to explore food-item and restaurant data from Swiggy and create an Excel-based summary of pricing, ratings, food preferences, and geographic/time-based patterns.

The workbook contains three sheets:
Sheet	Purpose
Swiggy Data	Source dataset containing 197,430 records and 14 columns
Analysis	KPI summary and pivot-style analysis tables
Dashboard	Dashboard worksheet included in the workbook


The analysis helps answer questions such as which states contribute the highest aggregate listed price, how Veg and Non-Veg price totals compare, and how aggregate price varies by month, weekday, and quarter.
Business Objectives
1. Summarize the total listed price represented in the dataset.
2. Understand the distribution of Veg and Non-Veg food records.
3. Compare aggregate listed price across months, weekdays, quarters, and states.
4. Review restaurant, city, food-category, and dish-level data.
5. Present important metrics in an easy-to-understand Excel summary.
Dataset Description
The source worksheet contains 197,430 rows and 14 columns, covering 1 January 2025 to 31 August 2025.
Column	Description
State	State associated with the restaurant listing
City	City associated with the restaurant listing
Order Date	Date field in the source dataset
Day	Day name
Quarter	Quarter label
Week	Week number
Restaurant Name	Restaurant name
Location	Restaurant locality
Category	Food/menu category
Dish Name	Food item name
Food type	Veg or Non-Veg
Price (INR)	Listed price in Indian Rupees
Rating	Rating value
Rating Count	Number of ratings associated with the listing


Key Metrics in the Workbook
The Analysis sheet reports the following summary values:
Metric	Value
Aggregate Price (INR)	₹5,30,12,505.77
Average Rating	4.34
Sum of Rating Count	55,91,574
Dish Records	1,97,430
Average Price per Dish Record (INR)	₹268.51


The workbook labels the aggregate price as Total Sales and the dish count as Orders. Because the provided source columns do not include an order ID or transaction amount, these should be interpreted as aggregate listed dish price and dish-record count—not verified transaction revenue or unique customer orders.
Analysis Included
The Analysis worksheet includes summary tables for:
- Monthly analysis: aggregate listed price by month.
- Food type analysis: comparison of Veg and Non-Veg aggregate listed price.
- Day-wise analysis: aggregate listed price by day of the week.
- Quarterly analysis: aggregate listed price, average rating, and dish-record count by quarter.
- State-wise analysis: aggregate listed price by state.
- Selected city analysis: comparison of selected cities.
- Week-wise analysis: aggregate listed price by week number.
Tools and Excel Skills
- Microsoft Excel
- Pivot Tables / Pivot-style summaries
- KPI summaries
- Data aggregation
- Date-based analysis
- Sorting and comparison
- Dashboard-oriented reporting
How to Use the Project
1. Download Swiggy excel dashboard (1).xlsx from this repository.
2. Open the workbook in Microsoft Excel.
3. Review the Swiggy Data sheet to understand the source fields.
4. Review the Analysis sheet to explore the KPI summary and analysis tables.
5. If the workbook contains PivotTables, refresh them after changing the source data using Data → Refresh All.
6. Use filters or slicers available in the workbook, if present, to explore different segments.
7. Validate any KPI definitions before presenting the results as business revenue or order metrics.
Key Findings
Based on the summary values in the provided workbook:
- Karnataka has the highest aggregate listed price among the states shown, at approximately ₹54.57 lakh.
- Veg records contribute approximately ₹3.46 crore in aggregate listed price, compared with approximately ₹1.84 crore for Non-Veg records.
- Quarter 2 has the highest aggregate listed price in the workbook, at approximately ₹1.99 crore.
- The average rating across the dataset is approximately 4.34.
- August is the final month represented in the source data; the dataset does not cover a full calendar year.
These findings describe the supplied dataset and its workbook summaries. They should not be interpreted as Swiggy's official company-wide financial results.
Important Data Notes
- The dataset contains no explicit Order_ID, customer ID, quantity, or confirmed transaction/revenue field.
- Price (INR) is treated here as a listed dish price. Summing it across rows gives an aggregate listed price, not necessarily realized sales revenue.
- The workbook's Orders count is based on the count of Dish Name records. It is not a distinct order count.
- The workbook's Average Order Value is calculated from aggregate price divided by dish-record count. It is more accurately described as average listed price per dish record unless transaction-level order data is available.
- The supplied dataset has no blank values in the 14 inspected columns.
- The period is January–August 2025, not a complete year.
Repository Structure
swiggy-food-data-analysis/
│
├── Swiggy excel dashboard (1).xlsx
└── README.md
Future Improvements
- Add a clearly documented Excel dashboard with KPI cards and charts.
- Add slicers for state, city, restaurant, food type, and date.
- Analyze top restaurants and popular dishes.
- Add a data dictionary and a documented data-cleaning process.
- If transaction-level data becomes available, calculate actual order count, revenue, and average order value.
- Extend the analysis to Power BI or SQL for additional portfolio practice.
Author
Bharti Koli
Aspiring Data Analyst
- LinkedIn: Bharti Koli
- GitHub: bhartikoli0105
This is an independent portfolio/practice analysis of the supplied dataset. It is not affiliated with or endorsed by Swiggy.
