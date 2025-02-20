# E-commerce Sales Analytics Dashboard in Power BI  

## Overview  
This project is an **E-commerce Sales Analytics Dashboard** built in **Power BI**. The dashboard provides insights into sales, profit, quantity sold, and customer trends using interactive visualizations.  

This project was completed as part of my **Leverify Data Analytics Course in June 2024**.  

## Features  
✔ **Total Sales, Profit, and Quantity Overview**  
✔ **Sales Breakdown by State and Customer**  
✔ **Payment Mode Distribution**  
✔ **Sales Trends by Month**  
✔ **Profitability Analysis by Category and Sub-category**  
✔ **Dynamic Filtering for Quarterly Analysis**  

---

## 📌 Dataset  
The project uses two datasets:  

- `Orders.csv`: Contains sales transactions, customer details, payment methods, and order amounts.  
- `Details.csv`: Contains product category, sub-category, and profit information.  

---

## 🔧 **Technologies Used**  
- **Power BI** – For data visualization  
- **DAX (Data Analysis Expressions)** – For advanced calculations  
- **Data Cleaning & Transformation** – Using Power Query  

---

## 📊 **Dashboard Breakdown**  

### 1️⃣ **KPIs (Key Performance Indicators)**  
- **Total Sales:** `438K`  
- **Total Quantity Sold:** `5615`  
- **Total Profit:** `37K`  
- **Average Order Value (AOV):** `121K`  

### 2️⃣ **Sales Analysis by Region & Customer**  
- **Top Performing States:** Uttar Pradesh, Rajasthan, and West Bengal  
- **Top Customers:** Harivansh, Madhav, Madan Mohan, and Shiva  

### 3️⃣ **Payment Mode Analysis**  
- **Cash on Delivery (COD) - 44%** (Most preferred)  
- **UPI - 21%**, **Debit Card - 13%**, **Credit Card - 12%**, **EMI - 10%**  

### 4️⃣ **Category-Wise Sales Trends**  
- **Clothing:** 63% of total sales  
- **Electronics:** 21%  
- **Furniture:** 17%  

### 5️⃣ **Profitability Analysis**  
- **Most Profitable Sub-Categories:**  
  - 📌 **Printers** (Highest profit)  
  - 📌 **Bookcases**, **Sarees**, **Accessories**, **Tables**  

### 6️⃣ **Time-Series Analysis**  
- **Highest Profit Months:** February, March, October, and November  
- **Loss in July and December** (Possible reasons: seasonal trends, high returns)  

---

## 🚀 **How to Use the Dashboard**  
1. **Download the repository** and open `ecommerce_sales_dashboard.pbix` in Power BI.  
2. **Explore Interactive Filters**: Use quarterly filters to analyze different time periods.  
3. **Customize as Needed**: Modify visuals or add additional insights based on business needs.  

---

## 🔥 **Advanced Concepts Used**  
### 🔹 **DAX Calculations**  
- **AOV Calculation:** `SUM(Sales Amount) / COUNT(Distinct Order ID)`  
- **Profit Margin:** `(Total Profit / Total Sales) * 100`  

### 🔹 **Power Query Data Cleaning**  
- Removed missing values  
- Standardized date formats  
- Created calculated columns for better insights  

---

## 📌 **Next Steps & Improvements**  
✅ Add **Forecasting using Power BI AI Features**  
✅ Implement **More Dynamic Filters (State, Category, Customer Segmentation)**  
✅ Use **Advanced DAX Measures for Deep Insights**  

---

## 📩 **Connect with Me**  
If you find this project useful, feel free to **star ⭐ the repo** and connect with me on LinkedIn!  


