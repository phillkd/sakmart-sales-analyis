
# SAKmart Sales Data Analysis — Product, Sales & Customer Insights

This project explores retail sales data from SAKmart (based on the Kaggle Walmart Sales Forecasting dataset) to uncover insights into product performance, sales trends, and customer behavior. The analysis was conducted using SQL Server Management Studio (SSMS) for data preparation and Power BI for visualization.

---

## 📁 Dataset


- **Source**: Kaggle Walmart Sales Forecasting competition
- **Size**: 1,000 transaction records. The dataset included the following columns:
- `Invoice ID`  
- `Branch`  
- `City`  
- `Customer Type`  
- `Gender`  
- `Product Line`  
- `Unit Price`  
- `Quantity`  
- `VAT`  
- `Total`  
- `Date`  
- `Time`  
- `Payment Type`  
- `COGS`  
- `Gross Margin Percent`  
- `Gross Income`  
- `Rating`
---

## 🎯 Project Objectives

- Identify top and underperforming product lines
- Evaluate sales patterns across time, location, and payment types
- Understand customer demographics and satisfaction
- Support strategic decision-making for sales optimization

---

## 🛠 Tools Used

- **SQL Server (SSMS)** – for data cleaning, feature engineering (e.g., extracting time of day, day of week, month)
- **Power BI** – for visual analysis and dashboard design

---

## 📊 Dashboard Overview

### 1. Product Analysis
- Revenue by Product Line
- Top-Selling Product Lines
- Product Category Performance (Good/Bad)
- Average Rating by Product Line

### 2. Sales Analysis
- Sales per Time of Day per Weekday (Stacked Column)
- Total Sales by Payment Type (Donut)
- VAT Distribution by City (Tree Map)
- VAT Paid by Customer Type (Bar)
- Total Sales Summary (Card)

### 3. Customer Analysis
- Quantity Purchased by Customer Type
- Gender Distribution by Branch
- Payment Preferences per Customer Type (Tree Maps)
- Average Rating per Day by Branch (Clustered Column)

---

## 📸 Visuals

You can view dashboard screenshots in the `/visuals/` folder.

| Sales Analysis |
![Sales_Analysis](https://github.com/user-attachments/assets/ed340a5e-8e3a-4c8f-87e2-017e89459a01)

| Product Analysis |
![Product_Analysis](https://github.com/user-attachments/assets/2f4c68e3-3513-4f13-9c4b-c14270e113ff)

| Customer Analysis |
![Customer_Analysis](https://github.com/user-attachments/assets/be6bbc9f-a4c6-4e98-8394-e24d7ce387bc)

---

## 🔍 Key Insights

- **Sports and Travel** is the highest-performing product line across all branches.
- Most sales occur in the **Afternoon**, especially on **Fridays**.
- **Members** purchase more products than **Normal** customers.
- **Ewallet** is the most preferred payment method across all branches.
- **Branch A** consistently shows strong sales and customer satisfaction.

---

## 📌 Author

**Philip Dagadu**  
SQL | Power BI | Data Analytics Projects
