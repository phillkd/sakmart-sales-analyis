
# SAKmart Sales Data Analysis — Product, Sales & Customer Insights

This project explores retail sales data from SAKmart (based on the Kaggle Walmart Sales Forecasting dataset) to uncover insights into product performance, sales trends, and customer behavior. The analysis was conducted using SQL Server Management Studio (SSMS) for data preparation and Power BI for visualization.

---

## 📁 Dataset

- **Source**: Kaggle Walmart Sales Forecasting competition
- **Size**: 1,000 transaction records
- **Branches**: Branch A, Branch B, Branch C
- **Cities**: Mandalay, Yangon, Naypyitaw
- **Fields**: Invoice ID, product line, quantity, unit price, tax, total, customer type, gender, payment type, date, time, rating

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

| Product Analysis | Sales Analysis |
|------------------|----------------|
| ![Product](visuals/Product_Analysis.png) | ![Sales](visuals/Sales_Analysis.png) |

_(Customer Analysis visual not embedded here, but should be uploaded manually)_

---

## 🔍 Key Insights

- **Sports and Travel** is the highest-performing product line across all branches.
- Most sales occur in the **Afternoon**, especially on **Fridays**.
- **Members** purchase more products than **Normal** customers.
- **Ewallet** is the most preferred payment method across all branches.
- **Branch A** consistently shows strong sales and customer satisfaction.

---

## 📌 Author

**Phil Dagadu**  
SQL | Power BI | Data Analytics Projects
