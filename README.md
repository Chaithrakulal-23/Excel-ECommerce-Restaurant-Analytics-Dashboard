# E-Commerce & Restaurant Analytics Dashboard
### Excel Data Analytics Portfolio Project

---

## Project Overview

An end-to-end data analytics project built entirely in Microsoft Excel,
combining E-Commerce Orders data and Zomato Restaurant data to derive
actionable business insights through cleaning, transformation, analysis,
and interactive dashboard visualization.

---

## Tools Used

- Microsoft Excel (PivotTables, PivotCharts, Slicers)
- Formulas: XLOOKUP, VLOOKUP, SUMIFS, COUNTIFS, AVERAGEIFS,
  INDEX-MATCH, IFS, IFERROR, TEXT, TRIM, PROPER, RANK

---

## Datasets

| Dataset | Source | Rows |
|---|---|---|
| Zomato Restaurant Data | Kaggle | 9,551 |
| E-Commerce Orders (List of Orders) | Kaggle | 500 |
| E-Commerce Orders (Order Details) | Kaggle | 1,500 |

---

## Project Phases

### Phase 1 — Data Exploration
- Used COUNTBLANK, COUNTIF to audit nulls and anomalies
- Identified 9 blank cuisines, 2148 unrated restaurants
- Checked for duplicates across both datasets

### Phase 2 — Data Cleaning (Zomato)
- Removed redundant columns
- Fixed blank cuisines using Find & Replace
- Added Rating Status, Cost Category, Popularity columns
- Standardized city and restaurant names using PROPER()
- Added Country Name using VLOOKUP with lookup table
- Fixed trailing spaces using TRIM()

### Phase 3 — Data Cleaning & Joining (E-Commerce)
- Joined List of Orders + Order Details using XLOOKUP
- Added 6 calculated columns:
  - Profit Margin % 
  - Profit Status (Profit / Loss / Breakeven)
  - Order Month
  - Order Year
  - Revenue Category
  - Quantity Category

### Phase 4 — Advanced Formula Analysis
- SUMIFS: Total Sales and Profit by Category and State
- COUNTIFS: Total Orders by Category
- AVERAGEIFS: Average Profit by Category
- RANK: Sales ranking by Category
- INDEX-MATCH: Top Sales State, Top Profit State,
  Worst Profit Category, Highest AVG Order Value State

### Phase 5 — PivotTables
- Monthly Sales Trend
- Category Performance
- State Performance
- Sub-Category Profit Analysis

### Phase 6 — Interactive Dashboard
- 4 KPI Cards: Total Sales, Total Profit, Total Orders,
  Total Restaurants
- Monthly Sales Trend (Line Chart)
- Sales by Category (Bar Chart)
- Profit by Sub-Category (Bar Chart)
- Sales by State (Bar Chart)
- Interactive Category Slicer

---

## Key Insights

- Electronics = highest sales category (₹1,65,267)
- Clothing = highest order volume (949 orders)
- Furniture = lowest profit margin (only 2%)
- November 2018 = most profitable month (₹11,619 profit)
- Madhya Pradesh = top state by sales (₹1,05,140)
- Maharashtra = top state by profit (₹6,176)
- India = 8,652 restaurants on Zomato (94% of dataset)
- Tables and Electronic Games = loss-making sub-categories

---

## Dashboard Preview

![Dashboard](https://github.com/Chaithrakulal-23/Excel-ECommerce-Restaurant-Analytics-Dashboard/blob/8c5f0a1c4390973dd0b00ee802b8e92185543448/DA_Project.png)

