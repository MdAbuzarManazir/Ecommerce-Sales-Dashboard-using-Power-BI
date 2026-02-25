# Ecommerce-Sales-Dashboard-using-Power-BI

# 1. About this project:

This project is a business intelligence solution built using Microsoft Power BI to help an e-commerce company track, analyze, and optimize its sales performance. Instead of looking at raw data in Excel sheets, the dashboard converts transactional data into interactive visuals and meaningful insights.

# 2. Objective of the Project:

2.1 Clear visibility of Sales, Quantity, and Profit.

2.2 Insights into top-performing states and customers.

2.3 Understanding of product category performance.

2.4 Analysis of payment behavior.

2.5 Monthly and quarterly profit trends.

# 3. Tools Used:

# 3.1 Microsoft Power BI Desktop:

3.1.1 Data modeling

3.1.2 DAX calculations

3.1.3 Data visualization

3.1.4 Interactive dashboard creation

# 3.2 Power Query Editor:

3.2.1 Data cleaning

3.2.2 Data transformation

3.2.3 Handling null values

3.2.4 Creating calculated columns

# 3.3 DAX (Data Analysis Expressions):

Used for:

1. Calculating Profit

2. Aggregations (SUM, COUNT)

3. Time intelligence (monthly trends)

# 3.4 Data Source:

Excel/CSV files (Orders & Details tables shown in the Data pane).

# 3.5 Data Model:

Two tables visible:

1. Orders

2. Details

# 3.6 Typical structure:

1. Order ID

2. Order Date

3. State

4. Customer Name

5. Category
   
6. Sub-Category

7. Quantity

8. Amount

9. Payment Mode

10. Profit

# 4. Relationship:

Orders ↔ Details (usually connected via Order ID)

# 5. 📊 Dashboard Components Explained:

#  5.1 KPI Insights (Core Metrics)

Though not shown as cards, visuals summarize

Sum of Amount (Sales)

Sum of Quantity

Sum of Profit

Total Sales = SUM(Details[Amount])

Total Profit = SUM(Details[Profit])

Total Quantity = SUM(Details[Quantity])

# 5.2 Sum of Amount by State (Bar Chart)

Shows which states generate the highest revenue.

# 5.3 Sum of Quantity by Category (Donut Chart)

# 5.4 Categories:

Clothing (63%)

Electronics (21%)

Furniture (17%)

# Insight:

Clothing dominates sales volume.

# 5.5 Sum of Amount by Customer Name

# Top customers:

- Harivansh

- Madhav
  
- Madan Mohan
  
- Shiva
  
# Insight:

Identify high-value customers for loyalty programs.

# 5.6 Quantity by Payment Mode (Donut Chart)

# Payment distribution:

COD (44%) – highest

UPI (21%)

Debit Card (13%)

Credit Card (12%)

EMI (10%)

# Insight:

Heavy reliance on COD.

# 5.7 Profit by Sub-Category (Horizontal Bar Chart)

# Sub-categories:

Printers (highest profit)

Bookcases

Saree

Accessories

Tables

# Insight:

Some sub-categories are more profitable even if quantity is lower.

# 5.8 Slicers (Interactive Filters)

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

# Completed, thank you....
