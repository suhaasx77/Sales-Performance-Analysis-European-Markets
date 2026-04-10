# Sales-Performance-Analysis-European-Markets

# 📊 Retail Sales Dashboard (Power BI Project)

## 📌 Project Overview

This project is an end-to-end **Power BI Sales Report** built for a retail business. It combines data from multiple sources like MySQL databases, Excel, and CSV files to create a fully interactive dashboard.

The project follows four key steps:

* Data collection & requirement gathering
* Data cleaning and transformation
* Report building with visuals and calculations
* Publishing with security and automation

The final output is a **Power BI App** that users can interact with to explore sales performance.

---

## 📊 Dashboard Highlights

The dashboard is designed as a **single-page view** showing the most important business insights.

<img width="839" height="778" alt="Sales report" src="https://github.com/user-attachments/assets/33884055-9610-4329-b394-387bba33369b" />


### 🔹 Key Metrics (KPI Cards)

* Total Revenue
* Gross Profit
* Units Sold

These provide a quick snapshot of overall performance.

---

### 🔹 Top Performers

* Displays the **Top 5 Sales Representatives**
* Based on the highest gross profit contribution

---

### 🔹 Sales Breakdown

* Revenue by product and subcategory
* Year-over-year sales analysis using a waterfall chart
* Product-level performance insights

---

### 🔹 Time-Based Analysis

* **Quarter-on-Quarter (QoQ)** revenue growth
* **Month-on-Month (MoM)** profit trends

These visuals help track business growth over time.

---

### 🔹 Daily Sales Insights

* Table showing **average daily sales**
* Conditional formatting highlights high and low performance days

---

### 🔹 Interactive Filters (Slicers)

Users can filter the entire dashboard using:

* Country
* Year
* Month

---

## 🛠️ Tools & Technologies

* **Power BI Desktop & Service**
* **Power Query** for data cleaning and transformation
* **DAX (Data Analysis Expressions)** for calculations
* **MySQL, Excel, CSV** as data sources

---

## 🔐 Security & Automation

* **Dynamic Row-Level Security (RLS)**

  * Users only see data relevant to their region
  * Implemented using `USERPRINCIPALNAME()`

* **Scheduled Data Refresh**

  * Configured using an On-Premises Data Gateway
  * Ensures data stays up-to-date automatically

---

## 🔍 Key Insights

* Identify top-performing products and categories
* Track revenue growth across months and quarters
* Highlight best-performing sales representatives
* Analyze daily sales trends and fluctuations

---

## 🚀 How to Use

1. Open the Power BI App
2. Use slicers (Country, Year, Month) to filter data
3. Click on charts to drill down into details
4. View insights tailored to your access (via RLS)

---

## 📈 Features

* Fully interactive dashboard
* Clean and user-friendly design
* Real-time data updates
* Secure data access control

---


