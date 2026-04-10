# Sales Performance Dashboard

## Overview
An interactive sales dashboard built in Power BI to analyze sales performance, profitability, and customer trends across regions, categories, and time periods. Designed to support data-driven business decisions by surfacing patterns that aren't visible in raw numbers.

---

## Tools & Technologies
- **Power BI** — Dashboard design and visualizations
- **DAX** — Calculated measures and KPIs
- **SQL** — Data extraction and transformation

---

## Dashboard Features

### KPIs
- Total Sales
- Total Profit
- Total Orders

### Visualizations
- Sales by Category & Sub-Category
- Monthly Sales Trend
- Top 10 Customers by Sales

### Filters / Slicers
- Region
- Year
- Category

---

## Data Summary

| Category        | Total Sales | Total Profit | Profit Margin |
|-----------------|-------------|--------------|---------------|
| Technology      | $836K       | $145K        | 17.3%         |
| Furniture        | $742K       | $18K         | 2.4%          |
| Office Supplies | $719K       | $122K        | 17.0%         |
| **Total**       | **$2.30M**  | **$285K**    | **12.4%**     |

---

## Key Insights
1. Furniture's 2.4% profit margin is the lowest across all categories — and the reason is two sub-categories. Tables lost $18K and Bookcases lost $3K, together wiping out $21K in profit. The other two sub-categories, Chairs and Furnishings, are actually profitable — but their gains get eaten up by these losses, leaving Furniture with just $18K profit from $742K in sales.
2. Copiers drive Technology's profitability despite lowest sales — with only $150K in sales, Copiers generate $56K in profit at a 37% margin. Machines, on the other hand, bring in $189K in sales but retain just $3K in profit (1.6% margin) — the biggest gap between sales volume and profitability in the entire dataset.
3. Central region sells more than South but earns less — Central generates $501K in sales compared to South's $392K, yet ends up with a lower profit margin (8% vs 12%). While every other region operates between 12–15% margin, Central stands out as the least efficient region, pointing to possible over-discounting or an unfavorable product mix.

---

## Dashboard Preview
<img width="792" height="666" alt="image" src="https://github.com/user-attachments/assets/beaf0914-362d-4b56-a0a2-84c1d2ba666a" />


---

## How to Use
1. Open the `.pbix` file in Power BI Desktop
2. Use the **Region**, **Year**, and **Category** slicers to filter the view
3. Hover over charts for detailed tooltips
4. KPIs update dynamically based on selected filters

---

## Author
Namratha Hegde
https://www.linkedin.com/in/namratha-hegde-116129174/

