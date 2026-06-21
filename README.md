# ApexPlanet Data Analytics Internship 
## Project Overview

This repository contains the work completed during the ApexPlanet Data Analytics Virtual Internship.

The project covers:
- Data Cleaning and Exploratory Data Analysis (EDA)
- SQL Fundamentals and Advanced SQL
- Python + SQL Integration
- Business Insight Generation
- Data Visualization and Dashboarding (Upcoming)

## Data Cleaning and Exploratory Data Analysis (EDA)

### Objective

Perform data cleaning and exploratory data analysis on the Superstore Sales Dataset to identify patterns, trends, and business insights.

### Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

### Tasks Performed

* Dataset Exploration
* Missing Value Analysis
* Duplicate Record Analysis
* Data Cleaning
* Sales Distribution Analysis
* State-wise Sales Analysis
* Category-wise Sales Analysis
* Region-wise Sales Analysis
* Profit Analysis

### Key Insights

* Missing values were identified and handled successfully.
* California generated the highest sales among all states.
* Technology and Office Supplies contributed significantly to total sales.
* Sales and profit varied across regions and categories.
* The cleaned dataset is suitable for further analysis.

## Task 2: SQL for Data Extraction and Business Analysis

### Objective

Use SQL and Python to extract, analyze, and generate business insights from the Superstore Sales dataset.

### Files

- notebooks/02_SQL_Analysis.ipynb
- notebooks/03_Python_SQL_Integration.ipynb

### Tools Used

- SQLite
- SQL
- Python
- Pandas
- Jupyter Notebook

### Skills Covered

- SELECT, WHERE, ORDER BY, LIMIT
- GROUP BY and HAVING
- Aggregate Functions
- Subqueries
- CTEs (WITH Clause)
- Views
- Window Functions
  - ROW_NUMBER()
  - RANK()
  - LAG()
  - LEAD()
- SQLite + Python Integration
- Business Analytics

### Business Questions Solved

1. Top products by sales
2. Top customers by spending
3. Sales by region
4. Profit by category
5. Average order value by region
6. Customer segment analysis
7. City-wise sales performance
8. Discount impact on profit
9. Regional profitability
10. Product ranking using window functions

### Key Insights

- West region generated the highest overall sales.
- Technology category contributed significantly to revenue and profit.
- High-value customers were identified for retention strategies.
- Discounts showed a measurable impact on profitability.
- Window functions enabled ranking and comparative analysis of business performance.
## Repository Structure
```text
apexplanet-data-analytics/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_SQL_Analysis.ipynb
│   └── 03_Python_SQL_Integration.ipynb
│
├── processed/
│   └── cleaned_superstore.csv
│
└── README.md
```