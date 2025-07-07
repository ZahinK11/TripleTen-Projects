# 🛍️ E-Commerce Funnel & Retention Analysis

## 📊 Sprint 3: Business Analytics Project

**Duration:** 1 hour 40 minutes  
**Tools Used:** Google Sheets  
**Dataset:** User event logs from an e-commerce platform  

---

## 📁 Project Overview

In this project, I was hired as a Junior Business Analyst at a fictional e-commerce company to transform raw user activity logs into meaningful business insights. My responsibilities included analyzing product conversion funnels, preparing user cohorts, calculating retention rates, and presenting the analysis in a polished, executive-ready format.

---

## 🎯 Business Goals

- Understand how effectively the website converts product views into purchases.
- Track customer retention using cohort analysis.
- Present data-driven insights to support product and marketing decisions.

---

## 🧠 Analysis Process

### Part 1: 🧭 Conversion Funnel

- Built a 3-stage funnel:  
  **Product Views → Cart Opens → Purchases**
- Used pivot tables to count unique users at each funnel stage.
- Calculated:
  - **Overall Conversion Rate**: Product Views → Purchases  
  - **Step-by-Step Conversion Rates**: Between each funnel stage

### Part 2: 📆 Cohort Analysis Preparation

- Filtered purchase data into a new `purchase_activity` sheet (4,845 rows).
- Identified each user’s **first purchase date** using pivot tables.
- Created new columns:
  - `first_purchase_date`
  - `event_month`
  - `first_purchase_month`
  - `cohort_age` (using `DATEDIF()`)

### Part 3: 📉 Retention Rates

- Created a `cohort_analysis` sheet showing user counts by month since acquisition.
- Built a `retention_rates` sheet with formulas to compute retention % for each cohort.
- Tracked users across a **0–4 month** window after acquisition.

### Part 4: 🗂 Spreadsheet Polishing

- Developed a **Table of Contents** with ordered sheet structure and descriptions.
- Completed an **Executive Summary** that:
  - Summarized funnel and retention results
  - Described dataset origin, assumptions, and methodology
- Applied formatting best practices for presentation clarity:
  - Frozen header rows
  - Consistent borders, fonts, and date formats
  - Clearly labeled formulas and metric columns

---

## 📊 Key Findings

- **Funnel Drop-Off**: Significant user drop-off between product views and cart opens.
- **Overall Conversion Rate**: (Insert actual %) from viewers to purchasers.
- **Highest Retention**: Seen in newer cohorts — suggesting improved engagement strategies.
- **Cohort Insights**: Retention sharply declines after Month 1 — highlighting areas for post-purchase engagement improvements.


## 🧠 Skills Demonstrated

- Funnel analysis with pivot tables
- Cohort analysis using date functions (`TEXT()`, `DATEDIF()`)
- Data transformation and cleaning in spreadsheets
- Executive reporting and spreadsheet design
- Spreadsheet-based KPI calculation and documentation



> _This project was completed as part of TripleTen’s Data Analytics Program — Sprint 3._
