# Man T-Shirts Data Analysis Dashboard

### Dashboard Link :
(https://app.powerbi.com/Redirect?action=OpenApp&appId=ae5cd900-b3a1-4951-884f-9fad19471ccc&ctid=bdc4f541-8f51-40f6-876b-1831a01b93fe&experience=power-bi)

## Problem Statement

This dashboard provides an end-to-end analysis of Men's T-Shirts data, helping retailers understand brand performance, discounts, and profit trends.  
It allows decision-makers to identify top-performing brands, evaluate discount strategies, and focus on brands with low profitability.

### Steps Followed 

- **Step 1:** Loaded dataset into **MS SQL Server Management Studio (SSMS)** and connected Power BI using the **MSSQL Server 'Database' option**.  
- **Step 2:** Performed **data cleaning** in SSMS (removed duplicates, handled missing values, standardized column names).  
- **Step 3:** Analyzed data to understand key attributes like sales price, MRP, brand, and profit percentage.  
- **Step 4:** Used **DAX** to create calculated columns:  
  - Discount %  
  - Profit %  
  - Cost Price  
- **Step 5:** Designed a **Brands Overview Page** with multiple interactive visuals.  
- **Step 6:** Added custom visuals from **AppSource** for better representation.  
- **Step 7:** Built key visuals:
  - **Bar Chart** → Top 5 Brands by Highest Average Discount %  
  - **Donut Chart** → Top 5 Brands by Variety Count  
  - **Ribbon Chart** → Top 5 Brands by Average Sales Price  
  - **Area Chart** → Top 5 Brands by Highest Average Profit %  
  - **Circle Graph** → Bottom 5 Brands by Profit %  
- **Step 8:** Published the report to **Power BI Service** and shared it securely using **Power BI Apps**.

### Snapshots

(Add screenshots of key pages here – e.g., Overview Page, Top 5 Brand Visuals, Bottom 5 Profit Chart.)

### Insights

- **Top 5 Brands by Average Discount %** → Identify which brands give maximum discounts and analyze their impact on sales.  
- **Top 5 Brands by Variety** → Helps understand brand assortment contribution.  
- **Top 5 Brands by Sales Price & Profit %** → Focus marketing and inventory strategies on high-profit brands.  
- **Bottom 5 Brands by Profit %** → Indicate areas where pricing strategy needs optimization.  

This dashboard enables data-driven decision-making to improve overall profitability, optimize discounting strategy, and manage brand mix efficiently.
