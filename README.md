# Data-analyst-intern-task2

Online Retail Sales Performance Dashboard

📁 Data Source:
File Name: Online Retail Data Set.xlsx

Description: This dataset contains transactional data for an online UK-based retail company between December 2010 and December 2011.

Key Columns:

InvoiceNo: Unique invoice number for each transaction.

StockCode: Unique code for each product.

Description: Name of the product.

Quantity: Number of products purchased.

InvoiceDate: Date of transaction.

UnitPrice: Price per product.

CustomerID: Unique ID for each customer.

Country: Country where the transaction occurred.

🎯 Objective:
To analyze sales performance, customer behavior, and product profitability across different regions using interactive Power BI visuals.

📌 Key Metrics (KPIs):
Total Sales = Quantity * UnitPrice

Total Orders = Distinct count of InvoiceNo

Total Customers = Distinct count of CustomerID

Average Order Value = Total Sales / Total Orders

Top Selling Products

Sales by Country

📈 Dashboard Pages Overview:
1. Executive Summary
Total Sales, Orders, Customers (KPI cards)

Monthly Sales Trend (Line Chart)

Sales by Country (Map Visual)

Top 5 Countries by Revenue (Bar Chart)

2. Product Performance
Top Products by Revenue and Quantity

Sales per Product Code and Description

Product Profitability Estimation

3. Customer Insights
Number of Returning vs. New Customers

Customer Orders by Country

Estimated Customer Lifetime Value

Invoice Table with filters

🧹 Data Cleaning Applied:
Removed rows with:

Missing CustomerID

Negative Quantity (assumed returns)

Created calculated column:

SalesAmount = Quantity * UnitPrice

Formatted InvoiceDate into month-year format for trend analysis
