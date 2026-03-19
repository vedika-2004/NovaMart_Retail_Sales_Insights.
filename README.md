# 🛒 NovaMart Retail Sales Insights
     A complete retail sales analysis project using Excel, Python, MySQL, and Power BI to uncover sales trends, customer insights, and business performance.

## 🧩 Project Overview
This project analyzes NovaMart's retail sales dataset to uncover business insights and sales trends. The goal is to transform raw retail data into meaningful insights that support data-driven decision making.

The project demonstrates a complete data analytics workflow using Excel, Python, MySQL, and Power BI.

## Objectives
- Analyze overall retail sales performance
- Identify top performing regions and product categories
- Understand yearly sales trends
- Calculate important business KPIs
- Build an interactive dashboard

## 📊 Dashboard Preview
![Dashboard Screenshot](./Screenshot%202026-03-18%20215002.png)

## 🗂️ Dataset Details

➢ Cleaned_dataset.csv – Contains retail sales transaction data used for analysis, including:

             Order ID, Order Date, Customer Name, Segment, Region, Category, Sub-Category, Product Name, Sales, Quantity, Profit, and Customer ID.


## Tools & Technologies Used
Data Cleaning: Microsoft Excel
Data Analysis: Python (Pandas, Matplotlib)
Database: MySQL
Data Visualization: Power BI

## Project Workflow
Excel → Python → MySQL → Power BI

1. Excel used for data cleaning
2. Python used for exploratory data analysis
3. MySQL used for storing dataset and running queries
4. Power BI used for dashboard visualization

## Data Cleaning
The dataset was cleaned using Excel and Python by:
- Handling missing values
- Converting date columns
- Checking data types
- Preparing dataset for analysis

## Exploratory Data Analysis
Python was used to perform:
- Total Sales Analysis
- Regional Sales Analysis
- Category-wise Sales Performance
- Yearly Sales Growth
- Average Revenue per Order

## MySQL Integration
The cleaned dataset was exported to MySQL using SQLAlchemy and PyMySQL.

Example:
df.to_sql("sales_data", engine, if_exists="replace", index=False)

# 📊 Power BI Dashboard

Dashboard Name: NovaMart_Retail_Sales_Analysis_Dashboard.pbix

### 🔹 Dashboard Features

» Key Performance Indicators (KPIs): Displays Total Sales, Total Profit, Total Orders, and Total Customers for a quick overview of overall business performance.

» Sales Trend Analysis: Monthly sales line chart highlighting seasonal patterns and fluctuations in revenue.

» Category Performance: Bar chart comparing sales across product categories to identify top-performing segments.

» Geographical Analysis: Map visualization showing sales distribution across different states for location-based insights. 🌍

» Regional Performance: Pie chart representing sales contribution by region (West, East, Central, South).

» Customer Segment Analysis: Donut chart showing how different customer segments (Consumer, Corporate, Home Office) contribute to total sales.

» Top Customers Insights: Bar chart displaying top customers based on their total sales contribution.

» Profit Analysis: Visualization of profit by sub-category to identify high and low-performing products.

» Interactive Filtering: Dynamic slicers for Region and Category enable users to explore data and gain customized insights.


## 🔍 Key Insights

• Technology category generates the highest sales among all categories.

• The West region contributes the largest share of total revenue.

• Consumer segment records the highest sales compared to other segments.

• Sub-categories like Copiers and Phones produce the highest profits.

• Monthly sales show fluctuations indicating seasonal demand patterns.


## Conclusion
This project demonstrates how Excel, Python, MySQL, and Power BI can be combined to perform end-to-end retail sales analysis.

