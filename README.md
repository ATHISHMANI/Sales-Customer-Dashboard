# 📊 Sales & Customer Performance Dashboards (Tableau)

## 📌 Overview  
This project builds two interactive Tableau dashboards — **Sales Dashboard** and **Customer Dashboard** — to help stakeholders (sales managers, executives, and marketing teams) analyze **sales performance, customer behavior, and profitability**.  

The dashboards provide **year-over-year comparisons**, **monthly & weekly trends**, and **top customer analysis** with interactive filters for deep exploration.  

🔗 **Live Dashboard Link:** [View on Tableau Public](https://public.tableau.com/views/SalesCustomerDashboards_17591109085900/CustomerDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  

---

## 📂 Dataset Details  

### 1. Customers.csv  
- **Shape:** 793 rows × 2 columns  
- **Columns:** `Customer ID`, `Customer Name`  

### 2. Location.csv  
- **Shape:** 632 rows × 5 columns  
- **Columns:** `Postal Code`, `City`, `State`, `Region`, `Country/Region`  

### 3. Orders.csv  
- **Shape:** 9,994 rows × 13 columns  
- **Columns:**  
  `Row ID`, `Order ID`, `Order Date`, `Ship Date`, `Ship Mode`,  
  `Customer ID`, `Segment`, `Postal Code`, `Product ID`,  
  `Sales`, `Quantity`, `Discount`, `Profit`  

### 4. Products.csv  
- **Shape:** 1,894 rows × 4 columns  
- **Columns:** `Product ID`, `Category`, `Sub-Category`, `Product Name`  

👉 Together, these datasets simulate an **order management system** with information on customers, products, transactions, and geographic locations.  
They serve as the **data backbone** for the Sales Dashboard and Customer Dashboard in Tableau.  

---

## ❓ Business Questions Addressed  

### 📈 Sales Dashboard  
- **What are the total sale**
