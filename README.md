# Customer Shopping Behavior Analysis

## Project Overview
This repository contains a full analytics workflow for understanding customer shopping behavior, from raw transactional data through data cleaning and Tableau-based visual analysis.

### Goal
Analyze customer purchase patterns, segment customers, and identify actionable insights for improving sales and marketing strategy.

## Data Source
- **Source:** Kaggle dataset
- **Files:** Raw transaction data and product/customer attributes
- **Format:** CSV / Excel (as provided by Kaggle)

## Data Cleaning
- **Tool used:** Power Query Editor (Excel / Power BI)
- **Steps performed:**
  - Imported raw data from Kaggle
  - Removed duplicates and invalid rows
  - Fixed column names and data types
  - Filled missing values and standardized categories
  - Created calculated columns (e.g. Total Sales, Order Age)
  - Exported cleaned dataset to the `Clean Data/` folder

## Analysis (Tableau)
- **Tool used:** Tableau Desktop
- **Key dashboards and sheets created:**
  1. **Sales Overview**
     - Total revenue, order count, average order value
     - Trend analysis by month and quarter
  2. **Customer Segmentation**
     - Recency, Frequency, Monetary (RFM) groups
     - High-value vs low-value customers
  3. **Product Performance**
     - Top-selling categories and products
     - Contribution to total revenue
  4. **Demographic Insights**
     - Purchase behavior by region/city
     - Channel and customer type comparisons
  5. **Basket and Upsell Analysis**
     - Product combinations and frequently bought together
     - Cross-sell and up-sell opportunity signals
  6. **Churn and Retention**
     - Repeat customer rate and cohort trends

## Folder Structure
- `Raw Data/` - Original Kaggle raw files
- `Clean Data/` - Processed datasets after Power Query cleaning
- `Result/` - Tableau workbook(s) and final output files

## Insights Summary
- Customer lifetime value increases with frequency and recency.
- A few product categories contribute >60% of revenue.
- West region has highest average order value; East region has fastest growth.
- Repeat buyers are the most profitable segment.

