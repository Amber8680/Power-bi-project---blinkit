
# 🛒 Blinkit Grocery Sales Dashboard — Power BI Project

## 📊 Project Overview

This project presents a comprehensive **interactive dashboard** built using **Power BI**, showcasing key insights and metrics from Blinkit's grocery dataset. The dashboard is designed to help stakeholders quickly understand sales performance, product trends, and operational efficiency.

## 💡 Objective

The primary objective of this project is to:

* Visualize Blinkit's grocery sales data in an insightful and interactive manner.
* Perform **data cleaning and transformation** using **Power BI Power Query Editor**.
* Apply **DAX (Data Analysis Expressions)** to create advanced measures and KPIs.
* Enable data-driven decision-making for business strategy and supply chain management.

---

## 📁 Dataset Description

* **Source**: Blinkit Grocery Sales Data (`BlinkIT Grocery Data.xlsx`)
* **Structure**: Contains sheets like `Orders`, `Products`, `Category`, and `Customers`.
* **Key Fields**:

  * Order ID, Order Date
  * Product Name, Category, Price
  * Quantity Ordered, Total Value
  * Customer City & State

---

## 🧼 Data Cleaning & Transformation

Performed using **Power Query Editor** in Power BI:

* Removed null and duplicate records
* Standardized column names and formats
* Merged related tables using primary keys
* Handled inconsistent date and price formats
* Created new columns (e.g., Month Name, Total Revenue)

---

## 🧠 DAX Measures Created

Implemented dynamic and reusable measures using **DAX**, such as:

* `Total Sales = SUM(Orders[Total_Value])`
* `Total Quantity = SUM(Orders[Quantity])`
* `Average Order Value = [Total Sales] / DISTINCTCOUNT(Orders[Order_ID])`
* `Sales Growth % = DIVIDE(([This Month Sales] - [Last Month Sales]), [Last Month Sales])`
* Time Intelligence functions for monthly/yearly trends

---

## 📌 Key Dashboard Features

* 📅 **Sales Trend Analysis** by month, quarter, and year
* 🥦 **Top-Selling Products** and **Categories**
* 🏙️ **Sales by City & State** using map visuals
* 🛍️ **Customer Purchase Behavior**
* 📈 **Interactive Filters** by category, product, city, and date range

---

## 📷 Screenshots


---

## 🔧 Tools & Technologies Used

* **Power BI Desktop**
* **Power Query Editor**
* **DAX (Data Analysis Expressions)**
* **Excel (for data exploration and validation)**

---

## 🚀 Outcomes

* Delivered a clean, interactive dashboard for stakeholders
* Enabled quick insights into Blinkit’s grocery sales patterns
* Applied core **BI concepts**, **data modeling**, and **visual storytelling**

---

