# 🛒 Online Retail — Sales Analysis

**Author:** Almat Apseit  
**Date:** 2025  
**Tools:** Python (pandas, numpy, matplotlib, seaborn), Power BI (optional)

---

## 📘 Project Overview

This project presents a full **exploratory data analysis (EDA)** of the [Online Retail dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data) from UCI Machine Learning Repository.  
It simulates a real-world data analytics workflow, from data cleaning and transformation to visualization and business insights.

The analysis was performed in **Python (Jupyter Notebook)** and can be easily reproduced using the provided notebook.

---

## 🎯 Objectives

- Understand the structure and key metrics of an online retail business  
- Identify the top-performing products and countries  
- Analyze monthly sales trends and seasonality  
- Calculate customer-level KPIs: LTV, average order value (AOV), and orders per customer  
- Conduct cohort analysis to measure **customer retention** over time  
- Provide actionable business recommendations based on findings

---

## 📂 Dataset

**Source:** [Kaggle — E-Commerce Data (Online Retail)](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
**File:** `OnlineRetail.csv` (≈541,000 rows, 8 columns)

| Column | Description |
|---------|--------------|
| InvoiceNo | Unique transaction ID |
| StockCode | Product code |
| Description | Product name |
| Quantity | Number of items sold |
| InvoiceDate | Date and time of purchase |
| UnitPrice | Price per item (GBP) |
| CustomerID | Unique customer identifier |
| Country | Customer country |

---

## 🧠 Analysis Steps

1. **Data Cleaning & Preparation**
   - Removed missing customer IDs and negative quantities  
   - Created `TotalPrice = Quantity × UnitPrice`  
   - Converted `InvoiceDate` to datetime  
   - Derived `InvoiceMonth` for time series aggregation  

2. **Descriptive Analysis**
   - Total revenue, number of orders, average order value  
   - Top 10 products by revenue and sales volume  
   - Revenue by country  

3. **Time Series Analysis**
   - Monthly revenue trends visualization  
   - Seasonal peaks (December holidays)  

4. **Customer Analysis**
   - LTV (Lifetime Value) and number of orders per customer  
   - Identification of top 5% customers contributing ~40% of revenue  

5. **Cohort Analysis**
   - Calculated monthly retention rates  
   - Visualized retention as a heatmap (first 12 months)

---

## 📊 Example Insights

- **Total Revenue:** £8.5M  
- **Active Customers:** 4.3K  
- **Top Product:** *Regency Cakestand 3 Tier*  
- **Main Market:** United Kingdom (~85% of total sales)  
- **Peak Season:** November–December  
- **Retention:** ~20% of customers make repeat purchases within 3 months

---

## 📈 Visualizations

- Monthly revenue line chart  
- Top products bar chart  
- Revenue by country  
- Customer LTV distribution  
- Cohort retention heatmap  

*(See notebook for full plots.)*

---

## 🧩 Recommendations

- Focus marketing campaigns on top-selling product categories  
- Use customer segmentation to target high-LTV clients  
- Expand efforts in top non-UK markets (Netherlands, Germany, France)  
- Introduce retention programs (email offers, loyalty bonuses)  
- Plan logistics and inventory around seasonal peaks  

---

## 🚀 Next Steps

- Build a **Power BI / Tableau dashboard** using processed data  
- Export key tables (monthly revenue, top products) for BI integration  
- Extend analysis with SQL-based queries for demonstration  
- Add a short business summary report (1-page PDF)

---

## 🧾 Files in Repository

| File | Description |
|------|--------------|
| `online_retail_analysis.ipynb` | Jupyter Notebook with complete analysis |
| `OnlineRetail.csv` | Dataset (download separately from Kaggle) |
| `README.md` | This documentation |
| *(optional)* Power BI Dashboard | For additional visual presentation |

---

## 🧰 Technologies Used

- Python 3.x  
- pandas, numpy  
- matplotlib, seaborn  
- Power BI / Tableau (optional)  
- Jupyter Notebook  

---

## 💡 About

This project was created as part of a **Data Analytics portfolio** to demonstrate practical analytical and visualization skills.  
It highlights the ability to derive business insights from raw e-commerce transaction data and communicate them effectively.

---

> 📍 *If you want to replicate this project, download the dataset from Kaggle, place it in the same directory, and run the notebook cells sequentially.*
