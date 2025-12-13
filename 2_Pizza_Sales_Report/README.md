# 🍕 Pizza Sales Power BI Dashboard

## 📊 Overview

This Power BI report provides an interactive analysis of pizza sales performance. It is designed to help stakeholders understand sales trends, customer ordering behavior, and business performance across time, categories, and products.

The dashboard enables quick, data‑driven insights to support decision‑making in areas such as inventory planning, marketing strategy, and operational efficiency.

---

## 🗂️ Dataset Description

The report is built on a transactional sales dataset containing order‑level details.

### Key Columns:

* **order_id** – Unique identifier for each order
* **order_date** – Date when the order was placed
* **pizza_name** – Name of the pizza sold
* **pizza_category** – Category (e.g., Classic, Veggie, Supreme)
* **pizza_size** – Size of the pizza (S, M, L, XL)
* **quantity** – Number of pizzas ordered
* **total_price** – Total revenue generated per line item

---

## 📈 Key Metrics & KPIs

The dashboard highlights the following performance indicators:

* **Total Revenue**
* **Total Orders**
* **Total Pizzas Sold**
* **Average Order Value (AOV)**
* **Average Pizzas per Order**

---

## 📊 Visualizations Included

* **Revenue Trend by Date** – Daily / monthly sales trends
* **Sales by Pizza Category** – Revenue and quantity comparison
* **Sales by Pizza Size** – Size‑wise contribution analysis
* **Top & Bottom Selling Pizzas** – Based on revenue and quantity
* **Orders by Day Name** – Weekday performance analysis

All visuals are interactive and respond to slicers and filters.

---

## 🎛️ Filters & Interactivity

Users can filter the report by:

* Date
* Pizza Category
* Pizza Size

Cross‑filtering is enabled to allow deeper exploration of the data.

---

## 🛠️ Data Preparation & Modeling

* Date fields were cleaned and converted to proper **Date** data types
* Invalid or blank dates were handled in **Power Query**
* Calculated columns and measures were created using **DAX**
* A clean star‑schema style model was followed for performance

---

## 🚀 How to Use the Report

1. Open the `.pbix` file in **Power BI Desktop**
2. Refresh data if required
3. Use slicers to explore trends and drill into specific insights
4. Publish to Power BI Service for sharing and collaboration

---

## 📌 Tools & Technologies

* **Power BI Desktop**
* **Power Query (M)**
* **DAX (Data Analysis Expressions)**

---

## 📄 File Information

* **File Name:** `pizza_sales_dashboard.pbix`
* **Report Type:** Interactive BI Dashboard

---

## 👤 Author

Created as part of a Power BI sales analysis project.

---

## 📝 Notes

* Ensure regional date settings match the dataset format
* Do not format numeric measures as text to preserve aggregation behavior

---

✅ *This README provides a complete overview for users, reviewers, and collaborators working with the Power BI report.*

