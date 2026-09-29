# PowerBI-Sales-Revenue-Analysis
Interactive Sales Revenue Analysis Dashboard built using Power BI, Power Query and DAX.

Sales Revenue Analysis Dashboard | Power BI

# Project Overview
This project is an interactive **Sales Revenue Analysis Dashboard** developed using Microsoft Power BI.
The dashboard provides a clear view of sales performance, profitability, order volume, product performance, regional performance, category performance, and customer segment performance.

# Project Objective
The main objective of this project is to analyze sales data and create an interactive business intelligence dashboard that helps users:
- Monitor overall sales and profit performance
- Analyze monthly sales trends
- Compare sales across different categories and regions
- Identify the top-performing products
- Analyze sales by customer segment
- Dynamically filter and explore business performance

# Tools & Technologies
- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning & Transformation
- Data Modeling
- Data Visualization
- Business Intelligence

# Key Performance Indicators (KPIs)
The dashboard includes the following KPIs:
- Total Sales
- Total Profit
- Total Orders
- Profit Margin
- Average Order Value (AOV)

# Dashboard Visualizations
The dashboard contains the following visualizations:

1. Monthly Sales Trend
Analyzes sales performance over time and helps identify changes in monthly sales.

2. Sales by Category
Provides a comparison of sales performance across different product categories.

3. Sales by Region
Shows sales distribution across different geographical regions.

4. Top 10 Products by Sales
Identifies the products generating the highest sales using a Top 10 filter based on Total Sales.

5. Sales by Segment
Analyzes sales contribution across different customer segments.

# Interactive Filters
The dashboard includes interactive slicers for:
- Year
- Region
- Category
- Segment
- Product
These slicers allow users to dynamically filter the dashboard and analyze specific business segments.

## DAX Measures
# Total Sales
Total Sales = SUM(Sales_Data[Sales])

# Total Profit
Total Profit = SUM(Sales_Data[Profit])

# Total Orders
Total Orders = DISTINCTCOUNT(Sales_Data[Order_ID])

# Profit Margin
Profit Margin = DIVIDE([Total Profit], [Total Sales])

# Average Order Value
Average Order Value = DIVIDE([Total Sales], [Total Orders])
