# CodeAlpha Project 2 — Exploratory Data Analysis (EDA)

## Overview
Complete EDA of the supplied e-commerce orders dataset using Python.

## Dataset
- 1,200 orders
- 14 original columns
- Date range: 2023-01-01 to 2025-06-30
- 1,189 unique customers
- 7 products
- Total revenue: 1,264,761.96
- Average order value: 1,053.97

## Questions Answered
1. What is the structure and quality of the dataset?
2. Are there missing values or duplicates?
3. Which products generate the most revenue?
4. Which order status is most common?
5. Which payment methods are most used?
6. Which referral sources generate the most revenue?
7. How does revenue change over time?
8. What does the order-value distribution look like?
9. Which orders are potential outliers?

## Key Findings
- Highest-revenue product: **Chair**
- Highest-revenue referral source: **Instagram**
- Highest-revenue month: **2024-06**
- Most frequent order status: **Cancelled**
- Duplicate rows: **0**
- Missing CouponCode values: **309**
- Potential TotalPrice outliers using IQR: **8**

## Cleaning
Missing CouponCode values were replaced with `NONE`. Date fields were converted to datetime and additional Year, Month, DayOfWeek and Quarter fields were created.

## Tools
Python, Pandas, NumPy, Matplotlib, Jupyter Notebook.

## Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/CodeAlpha_Project2_EDA.ipynb
```
