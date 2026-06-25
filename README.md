# Customer Behavior Analysis

[![Tools](https://img.shields.io/badge/Tools-Python%20%7C%20SQL%20%7C%20Power%20BI%20%7C%20Excel-blue)](https://github.com/your-username/Customer_behavior_analysis)
[![Data](https://img.shields.io/badge/Dataset-3.9K%20Records-green)]()

An end-to-end data analytics project designed to study consumer purchasing patterns, uncover demographic trends, and generate actionable business insights using Python, SQL, and Power BI.

---

## 📌 Project Overview

Customer Behavior Analysis provides a deep dive into consumer shopping data to understand how demographics, promotional discounts, seasonal shifts, customer reviews, payment preferences, and sales channels influence buying decisions. 

The ultimate goal of this project is to bridge the gap between raw data and executive decision-making—helping retail businesses improve customer engagement, optimize marketing spend, and maximize product revenue.

---

## ❓ Business Problem

A retail company is experiencing stagnant customer retention rates and wants to better understand customer shopping behavior to drive sales, improve satisfaction, and build long-term loyalty.

This project addresses a critical core question:
> **"How can consumer shopping data be leverage to identify high-value trends, improve customer engagement, and optimize marketing and product strategies?"**

---

## 🎯 Project Objectives

* 🛠️ **Clean & Prepare:** Process raw customer data, handle missing values, and transform columns using Python.
* 🔍 **Analyze:** Build and execute complex SQL analytical queries to explore purchasing habits.
* 📊 **Visualize:** Develop an interactive, multi-page Power BI dashboard to monitor key performance indicators (KPIs).
* 💡 **Strategize:** Turn data findings into concrete business recommendations for stakeholders.

---

## 📦 Dataset Information

* **Source:** Customer Shopping Dataset (CSV format)
* **Dataset Size:** 3,901 records
* **Key Features:** 
  * *Demographics:* Age, Gender, Location
  * *Transactions:* Purchase Amount (USD), Subscription Status, Frequency of Purchases
  * *Preferences:* Item Purchased, Category, Color, Size, Season
  * *Behavioral:* Review Rating, Shipping Type, Discount Applied, Promo Code Used, Payment Method

---

## 🛠️ Tools & Technologies

| Tool | Purpose | Key Libraries / Features Used |
| :--- | :--- | :--- |
| **Python** | Data Cleaning & Transformation | `pandas`, `numpy`, `matplotlib` |
| **SQL** | Exploratory Data Analysis (EDA) | Aggregate functions, Joins, CTEs, Window Functions |
| **Power BI**| Dashboard & Visualization | DAX Measures, Interactive Tooltips, Star Schema Modeling |
| **Excel** | Data Validation | Pivot Tables, Quick Profiling |
| **GitHub** | Project Documentation | Version Control & Portfolio presentation |

---

## 🔄 Project Workflow

### 1. Data Preparation (Python)
* Imported raw CSV data and inspected shapes, types, and summary statistics.
* Handled missing fields, resolved duplicate entries, and normalized text categories (e.g., standardizing text casing).
* Engineered features like age-group bins (`18-25`, `26-40`, `41-60`, `60+`) to enable deeper customer segmentation.

### 2. Exploratory Data Analysis (SQL)
* Uploaded cleaned data to an SQL database engine.
* Wrote targeted queries to isolate top-performing categories, revenue by location, and correlation between promotional codes and cart totals.

### 3. Dashboard Development (Power BI)
* Modeled data using a clean, normalized structure.
* Designed an interactive canvas focusing on **Revenue Performance**, **Customer Segmentation**, and **Buying Preferences**.

---

## 📊 Dashboard Preview

*Replace the placeholder image below with your actual exported Power BI screenshot once uploaded to your repository.*

![Power BI Dashboard View](Images/dashboard.png)

---

## 💡 Key Insights

Based on the analysis, several critical consumer trends were uncovered:

* 👥 **High-Value Demographics:** Customers in the **26–40 age demographic** generated the highest overall revenue, with a strong preference for clothing and footwear categories.
* 🏷️ **The Discount Paradox:** While promotional discounts successfully increased the *frequency* of purchases, the average transaction value (ATV) was **12% higher** among non-discounted transactions.
* 🍂 **Seasonal Fluctuations:** Fall and Winter seasons saw a significant spike in transaction volume (~35% increase) compared to Spring and Summer, heavily driven by outerwear purchases.
* 💳 **Payment Preferences:** Credit Cards and Digital Wallets accounted for over **65% of total transactions**, correlating with a lower shopping cart abandonment rate compared to cash or bank transfers.

---

## 🚀 Business Recommendations

Based on the insights above, the following data-driven actions are recommended:

1. **Targeted Campaigns:** Deploy personalized email marketing campaigns featuring winter apparel tailored specifically to the high-revenue 26–40 demographic.
2. **Revamp Loyalty Programs:** Pivot from generic flash discounts to a tiered loyalty rewards program. Since non-promo carts yield higher revenue, reward long-term retention via exclusive perks rather than constant price cuts.
3. **Optimize Digital Checkouts:** Streamline the checkout pipeline for mobile/digital wallets to reduce friction, as digital payment methods yield higher conversion volumes.
4. **Inventory Forecasting:** Scale up stock levels for high-demand apparel items 4–6 weeks prior to the Fall seasonal surge to prevent stockouts.

---

## 📂 Repository Structure

```text
Customer_behavior_analysis/
│
├── Dataset/             # Raw and Cleaned CSV files
├── Python/              # Jupyter Notebooks for data cleaning & preprocessing
├── SQL/                 # Analytical SQL scripts and queries
├── Dashboard/           # Power BI file (.pbix)
├── Images/              # Dashboard screenshots and visual assets
├── Report/              # Final PDF executive summary brief
└── README.md            # Project documentation (This file)
