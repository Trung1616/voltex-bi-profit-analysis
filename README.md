# 📊 Sales Performance Dashboard – Voltex Electronics

## Overview
This project analyzes the business performance of **Voltex Electronics**, a U.S.-based e-commerce electronics retailer, using an interactive **Power BI Business Intelligence dashboard**.

The dataset simulates operational data from **Q2–Q3 2024**, covering sales transactions, products, logistics, and customer feedback.  
The dashboard enables stakeholders to monitor business health, identify operational issues, evaluate product performance, and understand customer behavior to support **data-driven decision making**.

This project is part of a **Data Analyst portfolio** and is accompanied by a **presentation deck explaining the key insights and recommendations derived from the analysis**.

---

# 🎯 Business Objectives

The analysis focuses on four key business questions:

### 1️⃣ Business Health Monitoring
- Are **revenue, profit, and orders increasing or declining over time**?
- What are the **Month-over-Month (MoM)** trends for key business KPIs?
- Are **return rates or operational KPIs exceeding warning thresholds**?

### 2️⃣ Operational Performance
- Which **regions or shipping partners** affect delivery performance?
- What factors impact **On-Time Delivery (OTD)** and return rates?
- Are there operational inefficiencies affecting fulfillment performance?

### 3️⃣ Product Portfolio Performance
- Which **SKUs generate the highest revenue and profit**?
- Which products show **high return risk or margin erosion**?
- How does revenue contribution vary across **product categories and value tiers**?

### 4️⃣ Customer Behavior & Retention
- What is the **repeat purchase rate**?
- How does purchasing behavior vary across **customer segments**?
- How does **customer retention change over time** using cohort analysis?

---

# 📈 Dashboard Structure

The dashboard consists of **four analytical pages**, each designed for different stakeholders.

## Business Overview
Executive-level monitoring of key business KPIs including:
- Revenue
- Profit
- Orders
- Return Rate
- On-Time Delivery (OTD)
- Month-over-Month growth trends

---

## Operational Performance
Operational diagnostics focusing on:
- Shipping partner performance
- Delivery time and warehouse processing time
- Regional operational efficiency
- Return cost concentration using Pareto analysis

---

## Product Performance
Product portfolio analysis including:
- SKU-level profitability analysis
- Revenue vs Return Rate analysis
- Category and value-tier revenue contribution
- Margin diagnostics
- Drill-through analysis for SKU-level investigation

---

## Customer Insights
Customer behavior and retention analytics including:
- Revenue per customer
- Orders per customer
- Repeat purchase rate
- Customer segmentation (age, gender)
- Cohort-based retention analysis
- Return reason analysis

---

# ⚙️ Technical Implementation

The project uses a **star schema data model** to ensure efficient analytical performance.

## Data Model

Fact Table
- Orders / Sales transactions

Dimension Tables
- Products
- Customers
- Regions
- Shipping Partners
- Calendar

---

## Key Analytical Features

- Advanced **DAX calculations**
  - Month-over-Month (MoM)
  - Year-to-Date (YTD)
  - Profit Margin
  - Revenue Contribution %
  - Cohort Retention

- **Dynamic KPI Selection**
  - Field parameters for switching analytical metrics

- **Drill-through analysis**
  - SKU-level and regional diagnostics

- **Pareto analysis**
  - Identifying high-impact return cost drivers

- **Customer Cohort Analysis**
  - Tracking retention behavior across purchase cycles

---

# 📊 Key Insights

The analysis highlights several important patterns:

- Some **high-revenue SKUs also exhibit elevated return rates**, posing potential profitability risks.
- **Customer retention declines significantly after Month 3**, suggesting opportunities for improved engagement strategies.
- A small number of regions contribute to **a large portion of total return costs**, indicating operational improvement opportunities.
- Shipping partner performance varies significantly across regions, impacting **OTD and customer satisfaction**.

---

# 🛠 Tools & Technologies

- Power BI
- DAX
- Data Modeling (Star Schema)
- Cohort Analysis
- KPI Framework Design

---

# 📂 Project Structure
