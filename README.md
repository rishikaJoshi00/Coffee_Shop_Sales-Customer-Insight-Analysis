
# ☕ Coffee Shop Sales & Customer Insights Dashboard

## 📌 Project Overview
This project presents an end-to-end analysis of coffee shop sales data using SQL, Python, and Power BI. The goal is to extract meaningful business insights from transactional data and present them through an interactive dashboard.

The analysis focuses on understanding sales performance, customer behavior, and the impact of external factors such as weather conditions and discounts.

---

## 🛠️ Tools & Technologies
- Python (Pandas, Matplotlib)
- SQL (SQLite)
- Power BI (Data Visualization)

---

## 📂 Dataset Description
The dataset contains transactional data from multiple coffee shop locations, including:

- Store details (city, country, store type)
- Product information (category, product name, price)
- Customer data (age group, gender, loyalty status)
- Transaction details (quantity, total amount, payment method)
- External factors (weather condition, temperature, holidays, discounts)

---

## 🔍 Key Analysis Performed

### 📊 Sales Analysis
- Total revenue and transaction trends
- Revenue by product category and city
- Top-performing products based on sales

### 👥 Customer Analysis
- Revenue by age group and gender
- Loyalty vs non-loyalty customer behavior
- Average spend per customer

### 💳 Payment Insights
- Distribution of payment methods
- Customer preferences in payment types

### 🌦️ External Factors Analysis
- Impact of weather conditions on sales
- Discount-based purchasing behavior

---

## 🧠 SQL Analysis Highlights
- Revenue aggregation using GROUP BY
- Customer segmentation using DISTINCT counts
- Product performance analysis
- Discount impact calculations

---

## 🐍 Python Analysis
- Data cleaning and preprocessing using pandas
- Aggregations and exploratory data analysis
- Visualization using matplotlib

---

## 📈 Power BI Dashboard Features
- Interactive KPI cards (Revenue, Customers, Transactions, Avg Order Value)
- Sales breakdown by category and city
- Customer segmentation visuals
- Payment method distribution
- Weather impact on sales
- Dynamic filters for deeper analysis

---

## 📊 Key Insights
- Coffee products generate the highest revenue across locations
- Loyalty members contribute significantly to total sales
- Sales patterns vary across cities and weather conditions
- Discounts influence purchasing behavior but do not always reduce revenue
- Customer demographics impact buying trends

---

## 🚀 How to Run the Project

### Python & SQL:
1. Open the project in Python / Google Colab
2. Upload the dataset (`sales.csv`)
3. Run the notebook/script to perform analysis

### Power BI:
1. Open Power BI Desktop
2. Load the dataset (`sales.csv`)
3. Use the provided measures and visuals to recreate the dashboard

---

## 📁 Project Structure
coffee-sales-project
│── sales.csv
│── analysis.ipynb
│── sales.db
│── dashboard.pbix
│── README.md

## 🎯 Project Objective
To simulate a real-world business intelligence workflow by combining data analysis, SQL querying, and dashboard development to support data-driven decision-making.

---

## 💡 Future Improvements
- Add time-series analysis (daily/monthly trends)
- Integrate real-time data sources
- Enhance dashboard with advanced DAX measures

---
