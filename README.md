# 📊 E-commerce Customer Funnel Analysis Dashboard

An end-to-end SQL and Power BI project analyzing the customer purchase journey of an e-commerce website to identify conversion bottlenecks, customer behavior patterns, and opportunities to improve overall conversion performance.

---

# Table of Contents

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Dashboard Preview](#dashboard-preview)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Technical Skills Demonstrated](#technical-skills-demonstrated)
- [Repository Structure](#repository-structure)
- [Future Improvements](#future-improvements)

---

# Project Overview

The objective of this project is to analyze the customer journey through an e-commerce website and identify where customers drop off before completing a purchase.

Using SQL Server for data exploration and Power BI for visualization, this project transforms raw clickstream data into an interactive dashboard that helps stakeholders understand user behavior, evaluate marketing performance, and optimize the purchase funnel.

---

# Business Problem

Despite attracting thousands of website sessions, only a small percentage of visitors complete a purchase.

This project answers key business questions such as:

- Where do customers abandon the purchase journey?
- Which marketing channels generate the highest conversion rates?
- Which countries perform best?
- Do returning customers convert better than new customers?
- Which hours and days produce the highest conversions?
- How significant is cart abandonment?

---

# Dataset

The dataset contains customer browsing sessions across an e-commerce website.

**Key Fields**

- User ID
- Session ID
- Timestamp
- Page Type
- Device Type
- Country
- Referral Source
- Time on Page
- Items in Cart
- Purchase Status

The customer journey follows the funnel:

```
Home
   ↓
Product Page
   ↓
Cart
   ↓
Checkout
   ↓
Purchase
```

---

# Project Workflow

```
Raw Customer Journey Data
            │
            ▼
SQL Data Cleaning & Aggregation
            │
            ▼
Session-Level Analysis
            │
            ▼
KPI & Funnel Metrics
            │
            ▼
Power BI Data Model
            │
            ▼
DAX Measures
            │
            ▼
Interactive Dashboard
```

---

# Dashboard Preview

## Executive Summary

> *(Insert Executive Summary Dashboard Screenshot Here)*

The Executive Summary provides a high-level overview of website performance through:

- Total Sessions
- Total Purchases
- Conversion Rate
- Returning User Conversion Rate
- Cart Abandonment Rate
- Conversion Funnel
- Referral Source Performance
- Monthly Traffic & Conversion Trends
- New vs Returning User Comparison

---

## Funnel Deep Dive

> *(Insert Funnel Deep Dive Dashboard Screenshot Here)*

The Funnel Deep Dive explores customer behavior through:

- Hour × Day Conversion Heatmap
- Country-wise Conversion Rate
- Cart Completion vs Cart Abandonment
- Interactive Filters for Country, Device Type, Referral Source and Month

---

# Key Insights

### Funnel Performance

- 5,000 customer sessions were analyzed.
- Overall website conversion rate was **20.20%**.
- Only **1,010 sessions** completed a purchase.

### Customer Behavior

- Returning users converted at **21.00%**, outperforming new users (**18.86%**).
- Returning visitors demonstrated stronger purchase intent and higher engagement.

### Marketing Channels

- Google generated the highest conversion rate among all referral sources.
- Social Media delivered the lowest conversion performance.

### Cart Abandonment

- **36.84%** of customers who reached the cart abandoned their purchase before checkout.
- Checkout optimization presents a major opportunity for increasing conversions.

### Geographic Performance

- France achieved the highest conversion rate.
- Germany recorded the lowest conversion performance.

### Time-Based Analysis

- Conversion rates varied by both day of the week and hour of the day.
- Peak conversion periods can be leveraged for scheduling promotional campaigns and advertisements.

---

# Business Recommendations

Based on the analysis, the following actions are recommended:

- Improve the checkout experience to reduce cart abandonment.
- Increase marketing investment in high-performing referral sources.
- Develop targeted retention campaigns for first-time visitors.
- Schedule promotions during high-converting hours.
- Investigate low-performing geographic markets.
- Personalize the shopping experience for returning customers.

---

# Technical Skills Demonstrated

### SQL

- Common Table Expressions (CTEs)
- Views
- Window Functions
- CASE Statements
- Aggregate Functions
- Session-Level Analysis
- Funnel Analysis
- Cohort Analysis
- Time-Based Analysis

### Power BI

- Data Modeling
- DAX Measures
- KPI Cards
- Funnel Chart
- Heatmap Matrix
- Line Charts
- Bar Charts
- Donut Charts
- Interactive Slicers

### Business Analysis

- Conversion Funnel Analysis
- Customer Segmentation
- Cart Abandonment Analysis
- Marketing Performance Analysis
- Geographic Performance Analysis
- Cohort Analysis

---

# Repository Structure

```
📂 E-commerce-Funnel-Analysis
│
├── Data
│   └── customer_journey.csv
│
├── SQL
│   ├── Data_Cleaning.sql
│   ├── Funnel_Analysis.sql
│   └── Cohort_Analysis.sql
│
├── Power BI
│   └── Funnel Analysis.pbix
│
├── Images
│   ├── Executive Summary.png
│   └── Funnel Deep Dive.png
│
└── README.md
```

---

# Future Improvements

- Integrate Google Analytics 4 event-level data.
- Add revenue and average order value analysis.
- Build customer retention dashboards.
- Develop predictive models for purchase probability.
- Incorporate real-time streaming data for live dashboard monitoring.

---

## Author

**Nagarjunan Selvam**

If you found this project interesting, feel free to ⭐ this repository and connect with me on LinkedIn.
