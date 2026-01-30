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
