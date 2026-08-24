Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior to identify purchasing patterns, product preferences, customer segments, and factors influencing sales.

The project follows an end-to-end data analytics workflow, from data cleaning and exploration to SQL analysis and Power BI visualization.

## Tools & Technologies

* **Python** – Data cleaning, exploration and feature engineering
* **Pandas** – Data manipulation and preprocessing
* **PostgreSQL** – Database storage and SQL analysis
* **SQL** – Business and customer analysis
* **Power BI** – Interactive dashboard and data visualization

## Project Workflow

**Data Preparation → Exploratory Analysis → Feature Engineering → PostgreSQL → SQL Analysis → Power BI Dashboard**

### Data Cleaning & Preparation

* Checked dataset structure and summary statistics
* Handled missing values in the `Review Rating` column
* Used the **median rating within each category** for missing review ratings
* Standardized column names
* Checked data consistency and removed redundant information

### Feature Engineering

Created additional features including:

* `age_group`
* `purchase_frequency_days`

## SQL Analysis

The project answers several business questions, including:

* Revenue comparison by gender
* High-spending customers who used discounts
* Top-rated products
* Standard vs. Express shipping spending
* Subscribers vs. non-subscribers
* Discount-dependent products
* Customer segmentation
* Top 3 products within each category
* Relationship between repeat purchases and subscriptions
* Revenue contribution by age group

## Power BI Dashboard

An interactive Power BI dashboard was created to visualize the analysis and highlight key business insights.

The dashboard covers:

* Revenue analysis
* Product performance
* Customer segmentation
* Shipping behavior
* Subscription behavior
* Discount analysis
* Age-group revenue

## Key Business Recommendations

Based on the analysis:

* Improve subscription benefits to encourage sign-ups
* Strengthen customer loyalty programs
* Review discount strategies
* Promote highly rated and popular products
* Focus marketing efforts on high-revenue customer segments

## Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── powerbi/
│   └── Customer_Shopping_Behavior_Analysis.pbix
│
├── presentation/
│   └── Customer_Shopping_Behavior_Analysis.pptx
│
└── README.md
```

This project provided hands-on experience with the complete data analytics workflow, including **Python-based data preparation, PostgreSQL and SQL analysis, and Power BI visualization**, while translating data into actionable business insights.


**Python | Pandas | SQL | PostgreSQL | Power BI | Data Cleaning | Exploratory Data Analysis | Feature Engineering | Customer Segmentation | Data Visualization | Business Analytics**
