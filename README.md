# 📊 Customer Purchase Pattern Analysis Using Python

## 📖 Overview

This project analyzes customer purchasing behavior using an Online Retail dataset. The analysis follows a complete data analytics workflow, including data cleaning, feature engineering, exploratory data analysis (EDA), customer segmentation using RFM analysis, and business insight generation.

The goal is to help businesses understand customer purchasing patterns, identify high-value customers, discover sales trends, and support data-driven marketing and retention strategies.

---

## 🎯 Objectives

* Analyze customer purchasing behavior from retail transaction data.
* Clean and preprocess raw data for accurate analysis.
* Perform exploratory data analysis (EDA).
* Identify top customers, products, and countries by revenue.
* Analyze monthly, daily, and hourly sales trends.
* Segment customers using RFM (Recency, Frequency, Monetary) Analysis.
* Generate actionable business insights for decision-making.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

---

## 📂 Dataset Information

The dataset contains retail transaction records with the following fields:

* Invoice
* StockCode
* Description
* Quantity
* InvoiceDate
* Price
* Customer ID
* Country

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Removed missing values
* Removed duplicate records
* Removed cancelled transactions
* Converted appropriate data types
* Created a Revenue column
* Extracted Month, Day, and Hour from InvoiceDate

---

## 📈 Exploratory Data Analysis

The project includes analysis of:

* Customer purchasing behavior
* Product performance
* Revenue trends
* Country-wise sales
* Monthly revenue
* Daily revenue
* Hourly revenue

---

## 👥 RFM Customer Segmentation

Customers were segmented based on:

* **Recency** – How recently a customer made a purchase.
* **Frequency** – How often a customer purchases.
* **Monetary** – How much money a customer spends.

Customer segments include:

* 🏆 Champions
* 💎 Loyal Customers
* 😊 Potential Loyalists
* ⚠️ At Risk
* 😴 Lost Customers

---

## 📊 Visualizations

The notebook includes visualizations for:

* Monthly Revenue Trend
* Top 10 Products by Revenue
* Top 10 Customers by Revenue
* Revenue by Country
* Revenue by Hour
* Revenue Distribution
* Customer Segment Distribution
* Frequency vs Monetary Relationship

---

## 💡 Key Business Insights

* Identified the highest revenue-generating products.
* Identified high-value customers based on spending.
* Analyzed country-wise revenue performance.
* Discovered monthly and hourly purchasing trends.
* Segmented customers to support targeted marketing and customer retention strategies.

---

## 📁 Repository Structure

```text
Customer-Purchase-Pattern-Analysis/
│
├── Customer_Purchase_Pattern_Analysis.ipynb
├── README.md
```

---

## 🚀 Future Enhancements

* Build an interactive Power BI dashboard.
* Develop a Streamlit web application.
* Perform Customer Lifetime Value (CLV) analysis.
* Build a sales forecasting model using machine learning.

---

## 👨‍💻 Author

**Krishna Kalyan Gangula**

If you found this project useful, consider giving the repository a ⭐.
