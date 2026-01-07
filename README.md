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
- Revenue analysis by gender
- Identification of high-spending discount users
- Top-rated products based on customer reviews
- Spending comparison by shipping type
- Subscriber vs non-subscriber revenue analysis
- Detection of discount-dependent products
- Customer segmentation into New, Returning, and Loyal
- Top 3 products per category
- Subscription behavior of repeat buyers
- Revenue contribution by age group

## Power BI Dashboard
Built an interactive Power BI dashboard to visualize:
- Revenue trends by category, age group, and gender
- Customer segmentation distribution
- Subscription and shipping preferences
- Key KPIs including average purchase value and review ratings

## Key Business Insights
- Loyal customers contribute the majority of total purchases
- Male customers generate significantly higher revenue
- Targeted discounts can drive high-value purchases
- Young adults are the highest revenue-generating age group
- Express shipping users have a higher average spend

## Business Recommendations
- Promote subscription benefits to convert non-subscribers
- Strengthen customer loyalty programs
- Optimize discount strategies to protect margins
- Highlight top-rated and best-selling products
- Focus marketing efforts on high-revenue customer segments

## Future Enhancements
- Automate data ingestion and processing
- Add predictive analytics for customer behavior
- Deploy dashboards using Power BI Service

## Author
Anshuman Singh  
B.Tech (ECE) | Aspiring Data Analyst  
Skills: Python, SQL, PostgreSQL, Power BI, Data Analysis

