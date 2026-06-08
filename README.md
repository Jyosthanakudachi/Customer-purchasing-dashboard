# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 customer purchases across multiple product categories. The objective is to identify spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

## Tools & Technologies

* Python (Pandas, NumPy)
* PostgreSQL
* SQL
* Power BI
* Data Cleaning & ETL

## Dataset Information

* Total Records: 3,900
* Total Columns: 18
* Customer Demographics: Age, Gender, Location, Subscription Status
* Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
* Shopping Behavior: Discounts, Promo Codes, Previous Purchases, Frequency of Purchases, Review Ratings, Shipping Type

## Project Workflow

### Data Preparation Using Python

* Imported and explored data using Pandas.
* Handled missing values in review ratings.
* Standardized column names for consistency.
* Performed feature engineering by creating customer age groups and purchase frequency metrics.
* Loaded cleaned data into PostgreSQL for further analysis.

### SQL Business Analysis

Performed business-focused analysis including:

* Revenue analysis by gender.
* High-spending customer identification.
* Top-rated products analysis.
* Shipping type comparison.
* Subscriber vs non-subscriber revenue analysis.
* Discount-dependent product identification.
* Customer segmentation (New, Returning, Loyal).
* Top-performing products by category.
* Repeat buyer behavior analysis.
* Revenue contribution by age group.

### Power BI Dashboard

Developed an interactive Power BI dashboard to visualize:

* Customer demographics
* Revenue trends
* Product category performance
* Subscription behavior
* Customer segmentation
* Age-group based revenue insights

## Key Insights

* Loyal customers represented the largest customer segment.
* Certain products showed higher dependency on discounts.
* Subscription status influenced purchasing behavior and revenue contribution.
* Young adult customers generated the highest revenue.
* Express shipping customers showed slightly higher average purchase amounts.

## Business Recommendations

* Improve customer loyalty programs.
* Promote subscription benefits.
* Optimize discount strategies.
* Focus marketing efforts on high-value customer segments.
* Highlight top-rated products in promotional campaigns.

## Project Outcome

Successfully transformed raw transactional data into meaningful business insights using Python, SQL, PostgreSQL, and Power BI, enabling data-driven decision-making through interactive reporting and visualization.
