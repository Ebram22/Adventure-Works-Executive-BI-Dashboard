# 📊 Adventure Works: Executive Business Intelligence & Sales Analytics

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Tool](https://img.shields.io/badge/Tool-Power_BI-yellow)
![Data Model](https://img.shields.io/badge/Data_Model-Star_Schema-blue)

---

## 📌 Executive Summary
This project delivers an interactive, end-to-end **Power BI Business Intelligence solution** designed for **Adventure Works**, a global manufacturing company. The report transforms fragmented sales, product, customer, and regional operational data into strategic business insights.

The dashboard empowers executive stakeholders to track revenue growth, evaluate customer lifetime value (RFM segmentation), analyze product profitability, and simulate pricing strategies using advanced dynamic modeling.

👉 **[Click Here to Access the Live Interactive Report](https://app.powerbi.com/reportEmbed?reportId=8728cb16-fd52-4bd0-a788-3608798d5434&autoAuth=true&ctid=79454428-4dbe-401a-b2ab-64a5a7069e2b)** *

---

## 📸 Interactive Dashboard Preview

> *Demonstrating dynamic report navigation, RLS security view testing, and What-If price elasticity simulations:*

![Interactive Dashboard Demo](<video src="images/Price_Stimulation.mp4" controls autoplay loop muted width="100%"></video>)

---

## 💡 Key Business Questions Answered
* **Sales Performance:** Which product categories drive the highest net revenue and profit margins?
* **Product Optimization:** How do price changes directly impact forecasted profit margins across product lines?
* **Customer Segmentation:** Who are our most valuable customers (Champions vs. At-Risk), and what is our active customer retention rate?
* **Regional Dynamics:** Which countries demonstrate high return rates or margin compression?

---

## 🛠️ Architecture & Technical Features

### 1. Data Modeling & ETL (Power Query)
* **Star Schema Architecture:** Designed a clean multi-fact, multi-dimension schema to optimize DAX query performance and relationships.
* **ETL Transformations:** Handled missing values, standardized text fields, and created custom date tables to enable Time Intelligence analytics.

### 2. Advanced DAX & Analytical Mechanics
* **Dynamic Field Parameters:** Allowed users to toggle entire report canvases between `Revenue`, `Profits`, and `Orders` on the fly.
* **What-If Price Simulation:** Built dynamic DAX parameter sliders to simulate price increases/decreases and measure adjusted profit impact.
* **Time Intelligence Analytics:** Built metrics for YTD, Trailing 90-Day Active Customers, MoM Revenue growth, and Target vs. Actual variance tracking.

### 3. Data Governance & Security
* **Dynamic Role-Level Security (RLS):** Implemented dynamic user security rules based on `@USERPRINCIPALNAME()` to restrict regional managers to their assigned territories.

---

## 📊 Dashboard Page Breakdown

### 1. Sales Analysis Overview
Focuses on macro-level revenue, order volumes, profit performance, and top/bottom N performing products.

### 2. Product Performance & What-If Analysis
Focuses on individual SKU performance, return rates, and scenario testing via dynamic price sliders.

![Product Analysis](images/product%20analysis.JPG)

### 3. Customer Intelligence & RFM Segmentation
Tracks customer acquisition metrics, churn risk, income brackets, and customer lifecycle segments.

---

## 🚀 How to Run / Explore This Project
1. **Interactive Web Link:** Access the published live report directly via the link above.
2. **Static PDF Report:** Check `reports/` folder for a quick PDF export of all report pages.
3. **Power BI Desktop File:** Download the `.pbix` file located in `reports/` to inspect the underlying Star Schema model and DAX measures.

---

## ✍️ Author
* **Role:** Data Analyst / BI Specialist
* **LinkedIn:** [Your LinkedIn Profile URL]
* **Portfolio GitHub:** [Your GitHub Profile Link]
