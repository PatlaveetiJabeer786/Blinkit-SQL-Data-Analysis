# Blinkit-SQL-Data-Analysis
End-to-end SQL project analyzing Blinkit's sales, outlet performance, and customer ratings to derive actionable business insights.


# Blinkit Sales & Performance Analysis (SQL)

## 📊 Project Overview
This project performs a comprehensive analysis of Blinkit's sales data using SQL. The goal is to evaluate key performance indicators (KPIs) and identify trends across different outlet types, sizes, and locations.

## 🔑 Key Metrics Analyzed
- **Total Revenue:** ~$1.20M in total sales.
- **Average Sales:** Analysis of revenue per order.
- **Customer Satisfaction:** Average rating of 3.97 across all products.
- **Inventory Distribution:** Total count of 8,523 items categorized by fat content and item type.

## 🛠️ Tech Stack
- **Database:** Microsoft SQL Server (MS SQL)
- **Tool:** SQL Server Management Studio (SSMS)
- **Key Concepts:** CTEs, Window Functions (`OVER`), Aggregations, Case Statements, and Data Cleaning.

## 🚀 Key Insights
- **Top Performers:** Fruits, Vegetables, and Snacks drive the highest revenue.
- **Outlet Strategy:** Medium-sized outlets significantly outperform High-sized outlets in sales percentage (42% vs 20%).
- **Tier Analysis:** Tier 3 locations contribute the most to the total sales volume.

## 📂 How to use
1. Import the `.csv` file from the `/Data` folder into your SQL environment.
2. Run the cleaning script to standardize "low fat" and "regular" labels.
3. Execute the analysis queries to generate business reports.
