# Online Retail Analytics Dashboard
# Business Intelligence & Sales Performance Analysis
An end-to-end Business Intelligence project developed using Microsoft Power BI
 to analyze online retail transactions, customer purchasing behavior, product performance, and regional sales trends.

# Executive Summary

This project transforms raw retail transaction data into meaningful business insights through:
Data Cleaning
Data Transformation
KPI Development
Dashboard Design
Business Analysis

# The dashboard provides insights into:
Revenue performance
Product demand
Customer activity
Regional sales contribution
Seasonal business trends
Project Information
Category	Details
Tool Used	Microsoft Power BI
Dataset	online_retail.csv
Analysis Period	Dec 2010 – Dec 2011
Raw Dataset Size	530,374  Records
Clean Dataset Size	396,335 Records
Countries Covered	38
Total Revenue	£8.52 Million
Estimated Profit	£2.55 Million
Primary Market	United Kingdom

# Data Cleaning & Transformation
.  Removed null Customer IDs to ensure valid customer-level analysis
.  Removed negative quantity transactions representing cancelled or returned orders
.  Removed zero and negative UnitPrice values to maintain accurate revenue calculations
.  Removed duplicate transaction records to improve dataset consistency and reporting accuracy
.  Detected and removed extreme outliers from Quantity data to avoid distorted KPIs and sales trends
.  Cleaned and standardized StockCode values by removing non-product codes and inconsistent formats
.  Corrected data formatting and improved overall dataset quality using Microsoft Excel
 and Power Query in Microsoft Power BI
.  Created a clean and reliable dataset for accurate dashboard analysis and business insights

# The company lacked a centralized analytical solution to monitor:
Sales performance
Product demand
Customer activity
Regional revenue trends

# The raw dataset contained:

Missing values
Duplicate records
Invalid prices
Negative quantities
Extreme outliers
Inconsistent product codes

# These issues made direct analysis unreliable and could lead to inaccurate business decisions.

Project Objectives
Clean and standardize retail transaction data
Build business KPIs
Analyze customer and sales trends
Identify top-performing products and regions
Create an interactive Power BI dashboard
Generate business recommendations
Data Cleaning & Transformation

# Data preprocessing was performed using Microsoft Excel
 and Power Query.
Cleaning Steps
Removed null Customer IDs
Removed negative quantities
Removed invalid prices
Removed duplicate records
Removed extreme outliers
Standardized StockCode values
Outcome

# Improved data quality, reporting accuracy, and dashboard reliability.

KPI Metrics Developed
KPI	Purpose
Total Revenue	Measures overall sales
Estimated Profit	Evaluates profitability
Total Orders	Tracks completed transactions
Total Customers	Measures customer base
Average Order Value	Analyzes spending behavior
Revenue Contribution %	Measures country performance
Monthly Growth	Tracks business growth trends
Profit Estimation Logic

The dataset did not contain:

# Product Cost
Cost of Goods Sold (COGS)

Because actual cost data was unavailable, profit was estimated using a standard retail margin assumption of 30%.

# Why 0.3 Was Used
Retail businesses commonly operate with 25%–40% margins.
30% is considered a balanced industry-standard estimate.
It helps estimate profitability when cost data is unavailable.
Business Meaning

# For every:
£100 Revenue
Estimated Profit ≈ £30

This represents estimated gross profit, not exact net profit.

# Dashboard Features
Dashboard Component	Purpose
KPI Cards	Performance overview
Revenue Trend Chart	Monthly sales analysis
Country-wise Analysis	Regional contribution analysis
Product Performance Charts	Product demand analysis
Growth Analysis	Monthly growth tracking
Interactive Slicers	Dynamic filtering
Key Insights
# Revenue Performance
Total Revenue generated: £8.52 Million
Estimated Profit: £2.55 Million
# Regional Analysis
United Kingdom contributed the majority of total revenue.
Seasonal Trend
Q4 showed the strongest sales performance.
November recorded peak revenue.
# Product Analysis
High-volume products were not always the most profitable.
Data Quality Impact
Cleaning significantly improved reporting accuracy and KPI reliability.
Business Recommendations
# Area	Recommendation
Market Expansion	Reduce dependency on UK market
Inventory Planning	Increase stock before Q4
Marketing Strategy	Launch campaigns earlier
Product Strategy	Focus on high-margin products
Data Governance	Implement automated validation systems

# Conclusion
This project demonstrates the complete Business Intelligence workflow — from raw data preprocessing to dashboard development and business insight generation.

The final dashboard provides a structured analytical solution for monitoring sales performance, customer behavior, and regional business trends.
