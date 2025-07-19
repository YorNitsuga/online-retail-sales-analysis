# Sales Trend and Performance Analysis for a UK-Based Online Retail Store

## Project Overview
This project explores historical transaction data from a UK-based online retailer to uncover key sales patterns, product performance, and seasonal trends. The analysis focuses on identifying high-revenue periods, top-selling products, and regional sales distribution to help inform marketing, inventory, and operational decisions.

## Objective
To uncover actionable insights from sales data by:
- Identifying high-performing products and countries
- Analyzing sales seasonality and daily trends
- Detecting key time periods of peak and low performance
- Preparing the dataset for future customer-level analysis (RFM, segmentation, retention)

## Tools & Technologies
- **Python** (pandas, matplotlib, seaborn)
- **Jupyter Notebook**
- **Power BI** for interactive dashboards
- **GitHub** for version control and project documentation

## Dataset Summary
- **Source**: [Online Retail Dataset - UCI / Kaggle](https://www.kaggle.com/datasets/viridianachow/online-retail-uci-dataset)
- **Rows**: ~500,000
- **Time Period**: Dec 2010 – Dec 2011
- **Columns**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Data Cleaning Summary
- Removed missing `CustomerID` rows
- Removed duplicates
- Filtered out canceled orders and invalid quantities/prices
- Converted `InvoiceDate` to datetime format
- Created new features like `TotalPrice`, `YearMonth`, and `InvoiceDay`

## Exploratory Data Analysis (EDA)
Key EDA steps include:
- Descriptive statistics
- Univariate analysis (top products, quantity distribution)
- Time-based analysis (monthly trends, day-of-week patterns)
- Country-level sales contribution
- Visualizations using bar charts, line graphs, and heatmaps

## Key Insights
- **UK** accounts for over **89.92%** of transactions — strong domestic dependence
- The top-selling product alone generated over **₤168K**, indicating skewed revenue distribution
- **November 2011** had the highest revenue — ₤1.16M — confirming Q4 seasonality
- **Thursday**, **Tuesday**, and **Wednesday** had the highest revenue — suggesting mid-week buyer behavior
- **Sunday** consistently had the lowest revenue — limited weekend activity

## Repository Contents
- OnlineRetail.csv – Raw dataset
- Cleaned_OnlineRetail.csv – Cleaned dataset after preprocessing
- eda_analysis.ipynb – Exploratory Data Analysis
- clean_data.ipynb - Data cleaning and preprocessing notebook
- OnlineRetail_Dashboard.pbix – Interactive dashboard 

README.md – Project overview and documentation

## Future Work
- Implement RFM (Recency, Frequency, Monetary) analysis
- Segment customers based on behavior and value
- Explore retention and churn patterns
- Build cohort analysis for long-term engagement tracking

## Conclusion
This project lays the groundwork for deeper customer-level analytics by first ensuring data cleanliness and building strong foundational insights into the store's sales patterns. These insights can guide marketing campaigns, inventory decisions, and operational planning.

---
