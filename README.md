# 📊 Customer Purchase Pattern Analysis Using Python

## 📌 Project Overview

This project analyzes customer purchasing behavior using an Online Retail dataset. The objective is to understand customer buying patterns, identify top-performing products and customers, analyze sales trends, and segment customers using **RFM (Recency, Frequency, Monetary) Analysis**.

The project demonstrates the complete data analysis workflow, including data cleaning, feature engineering, exploratory data analysis (EDA), visualization, and customer segmentation.

---

## 🎯 Project Objectives

* Analyze customer purchasing behavior using transaction data.
* Clean and preprocess the dataset.
* Perform Exploratory Data Analysis (EDA).
* Identify top-selling products and high-value customers.
* Analyze monthly, daily, hourly, and country-wise sales trends.
* Perform RFM Analysis for customer segmentation.
* Generate actionable business insights to support business decisions.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

---

## 📂 Dataset Features

The dataset contains retail transaction information, including:

* Invoice Number
* Stock Code
* Product Description
* Quantity
* Invoice Date
* Unit Price
* Customer ID
* Country

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

* Removed missing values
* Removed duplicate records
* Removed cancelled orders (negative quantities)
* Converted data types
* Created a **Revenue** column
* Extracted **Month**, **Day**, and **Hour** from the invoice date

---

## 📈 Exploratory Data Analysis (EDA)

The analysis includes:

* Customer Analysis
* Product Analysis
* Revenue Analysis
* Country-wise Sales Analysis
* Monthly Sales Trend
* Daily Sales Trend
* Hourly Sales Trend

---

## 👥 RFM Customer Segmentation

Customers were segmented using **Recency**, **Frequency**, and **Monetary** values into the following categories:

* 🏆 Champions
* 💎 Loyal Customers
* 😊 Potential Loyalists
* ⚠️ At Risk
* 😴 Lost Customers

This segmentation helps businesses improve customer retention and develop targeted marketing strategies.

---

## 📊 Visualizations

The project includes visualizations such as:

* Monthly Revenue Trend
* Top 10 Products by Revenue
* Top 10 Customers by Revenue
* Revenue by Country
* Revenue by Hour
* Revenue Distribution
* Customer Segment Distribution
* Frequency vs Monetary Analysis

---

## 💡 Key Business Insights

* Identified the products generating the highest revenue.
* Identified the highest-value customers.
* Analyzed purchasing patterns across different countries.
* Discovered peak sales hours and monthly sales trends.
* Segmented customers to support retention and marketing strategies.

---

## 📁 Repository Structure

```text
Customer-Purchase-Pattern-Analysis/
│
├── Customer_Purchase_Pattern_Analysis.ipynb
└──  README.md/
```

---

## 🚀 Future Improvements

* Build an interactive Power BI dashboard.
* Develop a Streamlit web application.
* Implement customer lifetime value (CLV) analysis.
* Build a sales forecasting model using machine learning.

---

## 👨‍💻 Author

**Krishna Kalyan Gangula**

If you found this project useful, feel free to ⭐ the repository.
