# Customer-Behavior-Analysis
An end-to-end data analytics project that analyzes customer shopping behavior using Python, SQL, and Power BI. This project focuses on uncovering insights related to spending patterns, customer segments, product performance, and subscription behavior and presenting them through an interactive dashboard.

# Project Overview
This project analyzes transactional data from 3,900 customer purchases across multiple product categories. The goal is to help businesses make data-driven decisions related to marketing, sales, pricing, subscriptions, and customer retention by identifying meaningful patterns in customer behavior.

# Dataset 
- Total Records: 3900
- Total Columns: 18

# Tech Stack
- Python (Pandas & Numpy): Data cleaning, EDA, feature enginering, Data manipulation
- PostgrSQL: Business focused SQL analysis
- Power BI: Interactive dashboard for visualization of insights

# Exploratory Data Analysis (Python)
Key steps performed in Python:
- Loaded and explored data using pandas
- Checked structure and summary statistics
- Handled missing values in review ratings
- Standardized column names (snake_case)
- Engineered new features:
    - age_group
    - purchase_frequency_days
- Removed redundant columns after consistency checks
- Loaded cleaned data into PostgreSQL for SQL analysis

# SQL Business Analysis
Business questions answered using SQL:
1. Revenue comparison by gender
2. High-spending customers who still used discounts
3. Top 5 highest-rated products
4. Purchase behavior by shipping type
5. Subscriber vs non-subscriber spending analysis
6. Products most dependent on discounts
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 products per category
9. Subscription likelihood of repeat buyers
10. Revenue contribution by age group

# Power BI Dashboard
An interactive Customer Behavior Dashboard was built to visually present insights.

Dashboard Highlights:
- Total number of customers
- Average purchase amount
- Average review rating
- Subscription distribution
- Revenue & sales by category
- Revenue & sales by age group
- Interactive filters:
      - Gender
      - Subscription status
      - Category
      - Shipping type

  <img width="1197" height="792" alt="image" src="https://github.com/user-attachments/assets/23f09e76-23bf-4da8-86a6-5c17b865abe0" />


# Key Insights
- Clothing generates the highest revenue and sales volume
- Non-subscribers form the majority of customers, indicating subscription growth potential
- Young adults contribute the highest revenue among age groups
- Express shipping users tend to have higher average purchase amounts
- Loyal customers dominate the customer base, showing strong retention


# Business Recommendations
- Promote exclusive benefits to increase subscriptions
- Introduce loyalty programs to convert repeat buyers into long-term customers
- Optimize discount strategies to protect margins
- Highlight top-rated and best-selling products in campaigns
- Focus marketing efforts on high-revenue age groups and express shipping users

