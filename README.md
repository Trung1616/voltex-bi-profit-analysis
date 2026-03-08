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

# Voltex Electronics – Business Intelligence & Profitability Analysis

## Project Overview
This project analyzes the business performance of **Voltex Electronics**, a U.S. e-commerce electronics retailer, during **Q2–Q3 2024**.

The objective was to investigate the **profitability decline in Q3** by combining **business intelligence dashboard development** with **root cause analysis across revenue, costs, operations, and customer experience**.

The project demonstrates an **end-to-end Data Analyst workflow**, including:

- Data modeling
- KPI development
- Interactive dashboard design
- Root cause analysis
- Data-driven business recommendations

---

# Business Problem
During **Q3 2024**, Voltex Electronics experienced a significant **profitability decline**, even though revenue did not drop proportionally.

Key business questions:

- What caused the profit decline in Q3?
- Which cost drivers had the largest impact?
- Which regions, product categories, or logistics partners contributed most to return costs?
- How did operational issues affect customer experience?

---

# Data Model

A **star schema data model** was designed for scalable analysis.

### Fact Table
- `fact_orders`

### Dimension Tables
- `dim_customer`
- `dim_product`
- `dim_region`
- `dim_payment`
- `dim_shipping`
- `dim_return`

This structure allows flexible analysis across multiple dimensions such as:

- Product category
- Region
- Logistics partner
- Return reason
- Customer behavior

---

# Dashboard Overview

An interactive **Power BI Sales Performance Dashboard** was built to monitor key business metrics.

## Executive KPI Overview
- Revenue
- Orders
- Profit
- Profit Margin

## Operational Performance
- Late Delivery Rate
- On-Time Delivery (OTD)
- Shipping partner performance

## Product & Profitability Analysis
- Profit contribution by product category
- Return rate analysis
- Defective return cost breakdown

## Customer Experience
- Customer ratings
- Feedback sentiment distribution
- Impact of returns on satisfaction

Interactive features include:

- Drill-through navigation
- Dynamic KPI parameters
- Time comparisons (MoM, YTD)

---

# Analytical Methods

This project applies several analytical techniques commonly used in real-world business analytics:

- Profit decomposition (Revenue vs Cost drivers)
- Pareto analysis (return cost concentration)
- Root cause analysis across product, region, and logistics dimensions
- Customer experience linkage analysis
- Operational performance validation

Advanced **DAX measures** were implemented for:

- Month-over-Month (MoM)
- Year-to-Date (YTD)
- Contribution %
- Profit Margin
- Cohort Retention
- Dynamic KPI comparisons

---

# Key Insights

## Profitability Decline
Profit dropped significantly in Q3 due to both **revenue decline and increased operational costs**.

## Product Quality Impact
**Smartphones and Laptops accounted for over 85% of defective return costs**, with return rates reaching **14% and 12%** respectively.

## Logistics Partner Issue
A partner-specific logistics failure was identified where **late delivery increased from 1.47% in Q2 to 15.82% in Q3**, generating approximately **$174K in excess return costs**.

## Customer Experience Impact
Return-related orders showed extremely low customer ratings (**~1.4–1.5 / 5**) and contributed to **16% negative customer sentiment**, indicating significant dissatisfaction linked to product defects and delivery issues.

---

# Business Recommendations

## Short-Term Actions
- Address logistics partner performance issues and enforce SLA compliance.
- Implement focused quality control for high-return product categories.
- Improve customer recovery processes for return-related cases.

## Long-Term Improvements
- Introduce partner performance scorecards and monitoring systems.
- Integrate defect and return cost metrics into product decision-making.
- Build an integrated monitoring system linking quality, operations, and customer experience.

---

# Tools & Technologies

- Power BI
- DAX
- Data Modeling
- KPI Development
- Pareto Analysis
- Business Performance Analysis

---

# Project Structure

```
/data
/dataset

/dashboard
/powerbi_dashboard.pbix

/analysis
/capstone_presentation.pdf

README.md
```

---

# Skills Demonstrated

- Data Modeling (Star Schema)
- Business Intelligence Dashboard Development
- Advanced DAX
- Root Cause Analysis
- Business Performance Analysis
- Data-Driven Decision Making

---

# Acknowledgement

This project was completed as part of a **Data Analyst Capstone Project** guided by **Maz and Lucas from The Future Analyst**.

---

