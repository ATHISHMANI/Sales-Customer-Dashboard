📊 Sales & Customer Performance Dashboards (Tableau)
📌 Overview

This project builds two interactive Tableau dashboards — Sales Dashboard and Customer Dashboard — to help stakeholders (sales managers, executives, and marketing teams) analyze sales performance, customer behavior, and profitability.

The dashboards provide year-over-year comparisons, monthly & weekly trends, and top customer analysis with interactive filters for deep exploration.

🔗 Live Dashboard Link: View on Tableau Public

📂 Dataset Details

Customers.csv

Shape: 793 rows × 2 columns

Columns:

Customer ID

Customer Name

Location.csv

Shape: 632 rows × 5 columns

Columns:

Postal Code, City, State, Region, Country/Region

Orders.csv

Shape: 9,994 rows × 13 columns

Columns:

Row ID, Order ID, Order Date, Ship Date, Ship Mode,

Customer ID, Segment, Postal Code, Product ID,

Sales, Quantity, Discount, Profit

Products.csv

Shape: 1,894 rows × 4 columns

Columns:

Product ID, Category, Sub-Category, Product Name

👉 Together, these datasets simulate an order management system with information on customers, products, transactions, and geographic locations. They serve as the data backbone for the Sales Dashboard and Customer Dashboard in Tableau.

❓ Business Questions Addressed
Sales Dashboard

What are the total sales, profits, and quantity for this year vs last year?
→ KPI cards summarize yearly comparisons.

How do sales, profits, and quantity trend month-over-month?
→ Monthly trend lines with highest/lowest months highlighted.

Which product subcategories perform best in sales and profit?
→ Side-by-side comparisons of subcategories.

How do weekly sales & profits perform compared to the average?
→ Weekly trends with above/below average indicators.

Customer Dashboard

How many customers, orders, and sales per customer are there year-over-year?
→ KPI cards track growth and changes.

What are the monthly trends in customer KPIs?
→ Line charts highlight best/worst months.

How are customers distributed by number of orders?
→ Histogram shows engagement and loyalty patterns.

Who are the top 10 customers by profit?
→ Ranked table with rank, orders, sales, profit, and last order date.

🎨 Design & Interactivity

Dynamic Year Selection → View historical data by year

Navigation Controls → Switch easily between Sales & Customer dashboards

Interactive Filters → Product category, subcategory, region, state, city

Highlights → Automatic emphasis on best/worst months & top customers

🛠️ Tech Stack

Tableau Public → Dashboard design & interactivity

Python (pandas, numpy) → Data generation

CSV → Final dataset for Tableau
