# 🏙️ Manhattan Airbnb Investment Analysis

## 📊 Sprint 1: Spreadsheet Data Analysis

**Duration:** 2 hours 20 minutes  
**Type:** Spreadsheet-Based BI Project  
**Tools Used:** Google Sheets  

---

## 📁 Project Overview

This project focused on analyzing Airbnb data in Manhattan to help a client determine where and in what types of properties they should invest for vacation rentals. The goal was to use spreadsheet analysis techniques to:

- Identify the most attractive neighborhoods and property sizes.
- Determine how much money top listings generated.
- Provide actionable, data-driven investment recommendations.

---

## 🧩 Business Questions Addressed

1. **Which neighborhoods and property sizes are most attractive for vacation rentals?**
2. **Do different neighborhoods have different preferences for property sizes?**
3. **How much money did the most attractive listings generate?**

---

## 🔍 Key Analysis Steps

### 1. Data Cleaning
- Cleaned inconsistent entries in the `neighborhood` and `bedrooms` columns.
- Created `neighborhood_clean` and `bedrooms_clean` columns.
- Used `IF()` logic to convert empty bedroom entries into "0" for studio classification.
- Logged changes in a dedicated sheet for transparency and reproducibility.

### 2. Neighborhood Attractiveness
- Used `number_of_reviews_ltm` as a proxy for attractiveness.
- Built pivot tables to rank the top 10 neighborhoods.
- Visualized findings with a bar chart showing review counts.

### 3. Property Size Analysis
- Identified the most popular bedroom counts across top neighborhoods.
- Analyzed bedroom size preference per neighborhood using pivot tables.

### 4. Revenue Analysis
- Merged calendar data with listings using listing ID.
- Created a `revenue_earned` column to calculate nightly income when available.
- Filtered for top listings based on location + size match.
- Estimated annual income from 30-day sample data.

---

## 💡 Key Findings & Recommendations

### 🏘️ Neighborhoods & Property Types
- The top 3 neighborhoods with the highest rental activity based on reviews:
  - (Insert actual neighborhoods here from your pivot table)
- 1-bedrooms and studio apartments were the most popular overall.
- Harlem preferred 1-bedrooms, while Midtown had a higher preference for studios.

### 💰 Revenue Potential
- The top-performing listing earned **$29,940** in 30 days, projecting over **$359,280** annually.
- Listings in top neighborhoods with optimal bedroom sizes significantly outperformed others.

---

## 📈 Visualizations
- Pivot tables highlighting top neighborhoods and bedroom preferences.
- Bar chart showing the number of reviews for the top 10 neighborhoods.
- Revenue comparison table for top listings.

---

## 🗂 Project Structure

