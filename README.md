# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using retail transaction data to uncover insights into customer segments, purchasing patterns, product performance, and subscription impact. The analysis is performed using Python, SQL (PostgreSQL), and Power BI to support data-driven business decisions.

## Dataset Summary
- Total Records: 3,900 transactions
- Total Features: 18 columns
- Key Attributes:
  - Customer Demographics: Age, Gender, Location, Subscription Status
  - Purchase Details: Item Purchased, Category, Purchase Amount, Season
  - Shopping Behavior: Discount Applied, Purchase Frequency, Review Rating, Shipping Type
- Missing Values: 37 values in the Review Rating column

## Tools & Technologies
- Python (Pandas, NumPy)
- SQL (PostgreSQL)
- Power BI

## Data Preparation & Feature Engineering
- Loaded and explored the dataset using Pandas
- Handled missing values by imputing median review ratings by product category
- Standardized column names using snake_case format
- Created new features including age_group and purchase_frequency_days
- Removed redundant columns after consistency checks
- Loaded the cleaned dataset into PostgreSQL for SQL analysis

## SQL Analysis
Performed business-focused analysis using CTEs, window functions, joins, and aggregations:
- Revenue analysis
