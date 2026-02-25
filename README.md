# Ecommerce-Sales-Dashboard-using-Power-BI

# About this project:
This project is a business intelligence solution built using Microsoft Power BI to help an e-commerce company track, analyze, and optimize its sales performance. Instead of looking at raw data in Excel sheets, the dashboard converts transactional data into interactive visuals and meaningful insights.

# Objective of the Project:
1.To provide business stakeholders with
2.Clear visibility of Sales, Quantity, and Profit
3.Insights into top-performing states and customers
4.Understanding of product category performance
5.Analysis of payment behavior
6.Monthly and quarterly profit trends

# Tools Used:
# Microsoft Power BI Desktop:
Data modeling
DAX calculations
Data visualization
Interactive dashboard creation

# Power Query Editor:
Data cleaning
Data transformation
Handling null values
Creating calculated columns

# DAX (Data Analysis Expressions):
Used for:
Calculating Profit
Aggregations (SUM, COUNT)
Time intelligence (monthly trends)

# Data Source:
Excel/CSV files (Orders & Details tables shown in the Data pane).

# Data Model:
Two tables visible:
Orders
Details

Typical structure:
Order ID
Order Date
State
Customer Name
Category
Sub-Category
Quantity
Amount
Payment Mode
Profit

# Relationship:
Orders ↔ Details (usually connected via Order ID)

# 📊 Dashboard Components Explained:
# 1️⃣ KPI Insights (Core Metrics)
Though not shown as cards, visuals summarize:
Sum of Amount (Sales)
Sum of Quantity
Sum of Profit
Total Sales = SUM(Details[Amount])
Total Profit = SUM(Details[Profit])
Total Quantity = SUM(Details[Quantity])

# 2️⃣ Sum of Amount by State (Bar Chart)
Shows which states generate the highest revenue.

# 3️⃣ Sum of Quantity by Category (Donut Chart)
# Categories:
Clothing (63%)
Electronics (21%)
Furniture (17%)
# Insight:
Clothing dominates sales volume.

# 5️⃣ Sum of Amount by Customer Name
# Top customers:
Harivansh
Madhav
Madan Mohan
Shiva
# Insight:
Identify high-value customers for loyalty programs.

# 6️⃣ Quantity by Payment Mode (Donut Chart)
# Payment distribution:
COD (44%) – highest
UPI (21%)
Debit Card (13%)
Credit Card (12%)
EMI (10%)
# Insight:
Heavy reliance on COD.

# 7️⃣ Profit by Sub-Category (Horizontal Bar Chart)
# Sub-categories:
Printers (highest profit)
Bookcases
Saree
Accessories
Tables
# Insight:
Some sub-categories are more profitable even if quantity is lower.

# 8️⃣ Slicers (Interactive Filters)
🔘 Quarter Filter (Qtr 1–4)
Allows filtering data by quarter.
🔽 Dropdown Filter
Filters entire dashboard (possibly by year or category).
# Purpose:
Enhances user interaction and dynamic analysis.

# 🧠 Skills Demonstrated in This Project
✅ Data Cleaning
✅ Data Modeling
✅ DAX Calculations
✅ Data Visualization
✅ Business Insight Generation
✅ Dashboard Design
✅ Interactive Reporting

# 🎨 Design Features
Dark gradient theme (professional look)
Rounded visuals
Consistent color palette
Clean layout with visual grouping
Interactive cross-filtering enabled
