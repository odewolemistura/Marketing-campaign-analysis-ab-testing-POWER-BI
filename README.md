# 🍔 Power BI A/B Testing Dashboard – Fast-Food Campaign Performance Analysis

## 📌 Project Overview

A fast-food chain was planning to launch a new product and needed to determine the most effective promotional campaign out of three options. The item was introduced across 1,000+ locations in 9 different markets, and sales data was recorded over a 4-week testing period. This project evaluates which campaign resulted in the best performance using Power BI for end-to-end analysis and visualization.

---

## 📂 Data Source

- **Source**: Kaggle 
- **Format**: CSV
- **Records**: Over 1,000 store-level weekly sales entries
- **Features**:
  - `MarketID`
  - `MarketSize` (Small, Medium, Large)
  - `LocationID`
  - `AgeOfStore` (in years)
  - `Promotion` (Campaign 1, 2, or 3)
  - `Week` (1–4)
  - `SalesInThousands` (USD)

---

## 🛠 Tools Used

- **Power BI Desktop**
- **Power Query Editor** (Data cleaning & transformation)
- **DAX** (KPIs and calculated fields)
- **Excel/CSV** (initial data preview)

---

## 🧹 Data Cleaning & Preparation

- Confirmed correct data types (e.g., `Whole Number` for AgeOfStore)
- Removed duplicates and nulls 
- Created a new column for **Store Age Group** (e.g., 1–7, 8–14, 15–21, 22–30)
- Ensured consistent formatting for `Promotion` and `Week` fields
- Renamed columns for readability

---

## 📊 Exploratory Data Analysis (EDA)

The analysis focused on comparing the effectiveness of three different marketing promotions based on sales performance. To draw meaningful insights, three key business questions were explored using Power BI visualizations:

### 1. Which promotion generated the highest total and average sales overall?
- Bar charts and KPI cards were used to compare total and average `SalesInThousands` across the three promotions.
- This helped identify the most effective promotion in terms of overall impact.

### 2. How did each promotion perform across different market sizes (Small, Medium, Large)?
- A matrix visual displayed average sales for each promotion segmented by market size.
- This showed how promotional effectiveness varied based on the market's scale.

### 3. What was the weekly sales trend for each promotion over the four-week period?
- A line chart illustrated how sales changed from week to week for each promotion.
- This revealed whether some campaigns had stronger initial impact or more consistent growth over time.

These three analysis angles — **performance by campaign**, **by market size**, and **over time** — provide a comprehensive view of how each promotion performed, helping support a well-informed recommendation.


---

## 📊 Data Analysis (Visuals & Insights)

![image alt](https://github.com/odewolemistura/Marketing-campaign-analysis-ab-testing-POWER-BI/blob/621986387dfe98b2012e766bc3543a651e96dbf5/Campaign%20Dashboard%20Details.png)

![image alt]()

| Visual | Description |
|--------|-------------|
| **KPI Cards** | Total Sales, Average Sales per Store, Number of locations tested, Number of market tested |
| **Clustered Column Chart** | Compares average sales across the three promotions |
| **Line Chart** | Shows weekly sales trends for each promotion over 4 weeks |
| **Matrix Table** | Displays average sales by market size and promotion |
| **Slicers** | Interactive filters: Market Size, Store Age Group, Week|

---

## ✅ Findings / Results

- **Total Sales:** $29.3 million across 127 store locations in 10 markets.
- **Average Sales per Store:** Approximately $214,000.
- **Top Performing Campaign:**
  - **Campaign 3** achieved the highest total sales with **$10.4 million**
  - Followed closely by Campaign 1 (**$10 million**)
  - Campaign 2 had the lowest with **$8.9 million**

- **Weekly Sales Trends:**
  - **Campaign 1:** Consistently around **$58K** per week
  - **Campaign 3:** Slightly behind at **$55K–57K**
  - **Campaign 2:** Lowest performance with **$46K–47K** weekly

- **Average Sales by Market Size & Promotion:**
  - **Large Markets:** Campaign 3 (**$77K**) > Campaign 1 (**$75K**) > Campaign 2 (**$60K**)
  - **Medium Markets:** Campaign 1 (**$47K**) > Campaign 3 (**$45K**) > Campaign 2 (**$39K**)
  - **Small Markets:** Campaign 1 (**$60K**) ≈ Campaign 3 (**$59K**) > Campaign 2 (**$50K**)

---

## 💡 Recommendation

Based on total sales, weekly trends, and performance across all market sizes:

- **Campaign 3** is the most effective promotional strategy.
- It consistently outperformed the others and maintained strong results across all market segments.

👉 **Recommendation:** Adopt **Campaign 3** for the official product launch across all locations.




