# Voltex Electronics – End-to-End Business Intelligence & Profitability Analysis
# Sales Performance Dashboard – Voltex Electronics

## Overview
This project analyzes the business performance of **Voltex Electronics**, a U.S.-based e-commerce electronics retailer, using an interactive **Power BI Business Intelligence dashboard**.

The dataset simulates operational data from **Q2–Q3 2024**, covering sales transactions, products, logistics, and customer feedback.  
The dashboard enables stakeholders to monitor business health, identify operational issues, evaluate product performance, and understand customer behavior to support **data-driven decision making**.

---

# Business Objectives

The analysis focuses on four key business questions:

### 1️ Business Health Monitoring
- Are **revenue, profit, and orders increasing or declining over time**?
- What are the **Month-over-Month (MoM)** trends for key business KPIs?
- Are **return rates or operational KPIs exceeding warning thresholds**?

### 2️ Operational Performance
- Which **regions or shipping partners** affect delivery performance?
- What factors impact **On-Time Delivery (OTD)** and return rates?
- Are there operational inefficiencies affecting fulfillment performance?

### 3️ Product Portfolio Performance
- Which **SKUs generate the highest revenue and profit**?
- Which products show **high return risk or margin erosion**?
- How does revenue contribution vary across **product categories and value tiers**?

### 4 Customer Behavior & Retention
- What is the **repeat purchase rate**?
- How does purchasing behavior vary across **customer segments**?
- How does **customer retention change over time** using cohort analysis?

---

# Dashboard Structure

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

# Technical Implementation

The project uses a **star schema data model** to ensure efficient analytical performance.

## Data Model

Fact Table
- Orders 
Dimension Tables
- Products
- Customers
- Regions
- Shipping 
- Return
- Payment

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

# Key Insights

The analysis highlights several important patterns:

- Some **high-revenue SKUs also exhibit elevated return rates**, posing potential profitability risks.
- **Customer retention declines significantly after Month 3**, suggesting opportunities for improved engagement strategies.
- A small number of regions contribute to **a large portion of total return costs**, indicating operational improvement opportunities.
- Shipping partner performance varies significantly across regions, impacting **OTD and customer satisfaction**.

---

# Tools & Technologies

- Power BI
- DAX
- Data Modeling (Star Schema)
- Cohort Analysis
- KPI Framework Design

---

# Capstone Business Analysis

In addition to dashboard development, a **consultant-style analytical investigation** was conducted to diagnose a **profitability decline observed in Q3 2024**.

The analysis was presented through a structured slide deck and followed a business diagnostic approach including:

- Performance comparison between **Q2 and Q3**
- **Profit decomposition** to isolate revenue and cost drivers
- **Return cost Pareto analysis by region**
- Deep dive into **product category performance**
- **Shipping partner delivery reliability validation**
- **Customer experience impact analysis**

This investigation aimed to identify **root causes behind margin erosion** and translate insights into actionable business recommendations.

---

# Key Findings from the Investigation

The deeper analysis revealed several critical operational drivers behind the profitability decline:

- **Smartphones and Laptops accounted for over 85% of defective return costs**, with return rates of approximately **14% and 12%** respectively.
- A logistics partner performance breakdown caused **late delivery rates to increase from 1.47% in Q2 to 15.82% in Q3**, generating approximately **$174K in excess return costs**.
- Return-related transactions were strongly associated with **extremely low customer ratings (~1.4–1.5 / 5)** and higher negative sentiment.
- The findings revealed a systemic **Quality → Returns → Customer Experience** impact chain affecting overall business performance.

---

# Business Recommendations

Based on the analytical findings, the following actions were recommended:

## Short-Term Actions
- Address shipping partner performance issues and enforce delivery SLA compliance.
- Implement targeted quality control for high-return product categories.
- Improve customer recovery processes for return-related cases.

## Long-Term Improvements
- Introduce partner performance monitoring frameworks.
- Integrate return and defect metrics into product decision processes.
- Develop a unified monitoring system linking product quality, logistics performance, and customer experience.

---

# Project Skills Demonstrated

This project demonstrates practical Data Analyst capabilities including:

- Business Intelligence Dashboard Development
- Data Modeling with Star Schema
- Advanced DAX KPI Modeling
- Root Cause Analysis
- Operational Performance Diagnostics
- Data-Driven Business Recommendations

---

# Acknowledgement

This project was completed as part of a **Data Analyst Capstone Project** guided by **Maz and Lucas from The Future Analyst**.
