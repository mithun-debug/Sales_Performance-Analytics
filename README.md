# Sales & Performance Analytics

An end-to-end Excel dashboard analyzing sales, ratings, and order trends for a food delivery platform — built to uncover revenue patterns across states, cities, cuisines, and time periods.

![Dashboard Preview](https://github.com/mithun-debug/Sales_Performance-Analytics/blob/main/Screenshot_Dashboard.png)

---

##  Problem Statement

Food delivery platforms generate massive volumes of order-level data daily, but without proper analysis this data rarely translates into actionable insight. This project analyzes order-level data to answer key business questions:

- How do sales trend on a monthly, weekly, and daily basis?
- Which states and cities drive the most revenue?
- How does demand differ between Veg and Non-Veg food types?
- Which restaurants and dishes perform best?
- How do Sales, Ratings, and Orders compare across quarters?

---

##  Business Requirements

### KPIs Tracked
| KPI | Description |
|---|---|
| Total Sales (₹) | Overall revenue generated from food orders |
| Average Rating | Customer satisfaction across all restaurants |
| Average Order Value (₹) | Revenue generated per order |
| Ratings Count | Total number of customer reviews |
| Total Orders | Number of food orders received |

### Charts Built
- **Monthly Sales Trend** — Fluctuation in total sales month by month
- **Daily Sales Trend** — Order/revenue variation across days of the week
- **Sales by Food Type** — Veg vs Non-Veg revenue contribution
- **Sales by State** — Geo-map visualization of state-wise revenue
- **Quarterly Performance Summary** — Combined view of Sales, Ratings & Orders by quarter
- **Top 5 Cities by Sales** — Leading revenue-contributing cities
- **Weekly Trend Analysis** — Week-over-week sales consistency and peaks

---

##  Dataset Overview

Order-level data with fields including:

`State`, `City`, `Order Date`, `Day`, `Quarter`, `Week`, `Restaurant Name`, `Location`, `Category`, `Dish Name`, `Food Type`, `Price`, `Rating`, `Rating Count`

---

##  Tools & Techniques

- **Microsoft Excel** — Pivot Tables, Pivot Charts, Power Query
- **Feature Engineering** — Derived new columns (`Day`, `Quarter`, `Week`, `Food Type`) from raw order data to enable deeper time-based and categorical analysis
- **Interactive Slicers** — Month, Category, Restaurant Name filters
- **Map Visualization** — State-wise sales using Excel's geo-mapping (Bing Maps)
- **Data Cleaning** — Structuring raw order data into an analysis-ready format
- **Dashboard Design** — Single-page interactive dashboard with dynamic filtering

---

## 📊 Key Highlights

- Analyzed **197.43K+ orders** totaling **₹53.01M** in sales
- Average customer rating of **4.34** across all restaurants
- Average order value of **₹268.51**
- Identified **Bengaluru** as the top-performing city by sales
- Veg items contributed **65%** of total sales vs **35%** for Non-Veg

---

## 📁 Repository Structure
```
├── dashboard_preview.png       # Dashboard screenshot
├── Swiggy_Raw_Data.xlsx         # Raw Data
├── problem_statement.png       # Charts & KPI's
├── Swiggy_Analysis.xlsx        # Main Excel file
└── README.md
```

---

---

## **Mithun M**

Aspiring **Data Analyst**

### Technical Skills

`Excel` `Data Analytics` 

---
