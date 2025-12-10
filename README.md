# Amazon Products Sales Analytics 

## Project Overview
This end-to-end analytics solution explores Amazon product performance using real transactional retail data. The project transforms raw sales records into insights that support product strategy, category performance tracking, inventory planning, pricing evaluation, and customer engagement optimization, all delivered through an interactive Power BI dashboard.

Using visual analytics, the solution highlights product sales behavior across time, customer engagement via reviews, top-performing product categories, and high-impact SKUs driving revenue and growth.

<img width="1010" height="566" alt="Amazon Products" src="https://github.com/user-attachments/assets/3d36657c-3afb-467f-8e06-d55282744102" />

---

## Business Need & Problem Statement
Amazon requires a clear analytical view of product performance trends to support strategic sales decisions. Key questions included:

- How do sales and engagement trends fluctuate across months and weeks?
- Which product categories contribute most to revenue and customer demand?
- Which products drive the highest YoY and QTD revenue growth?
- How do reviews correlate with product performance and buyer interest?
- What are the top-performing individual SKUs?

The goal was to build an interactive dashboard allowing stakeholders to:

- Track year-to-date (YTD) and quarter-to-date (QTD) revenue performance
- Monitor customer buying behavior across time periods
- Identify high-value and high-volume product categories
- Compare category contribution to total revenue and product distribution
- Surface top products by sales and review activity for business decisions

---

## Analytical Objectives
- Measure total YTD and QTD sales performance.
- Analyze category contribution to revenue growth and sales distribution.
- Identify top products driving revenue and customer engagement.
- Evaluate sales trends across months and weeks to understand demand cycles.
- Support category growth, pricing optimization, and strategic inventory planning.

---

## Workflow Summary

| Stage | Description |
|-------|------------|
| **1. Requirement Gathering** | Identified key KPIs, stakeholder metrics, and performance questions. |
| **2. Data Walkthrough** | Reviewed product fields, category hierarchies, and sales metrics. |
| **3. Data Cleaning** | Standardized categories, fixed inconsistencies, validated missing values. |
| **4. Data Modeling** | Structured a clean analytical model for filtering and DAX calculations. |
| **5. DAX Calculations** | Built KPI measures including YTD/QTD sales, category distribution, and top-product ranking. |
| **6. Dashboard Development** | Created an interactive dashboard with drill-downs, slicers, conditional formatting, and bookmarks. |
| **7. Insights Generation** | Interpreted patterns into business-ready insights and recommendations. |

---
## Dataset
The dataset contains 89,082 product records across multiple categories, including detailed metrics such as pricing, units sold, revenue, ratings, and customer review volume, providing a rich foundation for analyzing marketplace trends, product performance, and consumer engagement at scale.

<img width="1152" height="628" alt="Amazon Table" src="https://github.com/user-attachments/assets/612592dd-bc9a-4d37-a9ed-02f71ece7e09" />


## Model

<img width="1252" height="564" alt="Model" src="https://github.com/user-attachments/assets/f6e55c3d-4ad1-49cf-93c4-52b1e0328539" />


---

## Dashboard & Visualizations

### 1️⃣ Amazon Products Dashboard
A consolidated analytics view summarizing overall sales performance, seasonal behavior, category contribution, and SKU-level rankings. It presents key metrics such as YTD and QTD sales, total units sold, and review volume through high-level KPI cards, while time-based charts reveal both monthly and weekly sales patterns. 

<img width="1010" height="566" alt="Amazon Products" src="https://github.com/user-attachments/assets/8be37f64-dc16-44d2-8a8b-6037ee96c19f" />


Category-level segmentation highlights revenue distribution and percentage impact across product groups, and top-performer visuals showcase the highest-earning and most-reviewed products for rapid comparison and decision-making.

---

## Key Insights

- **Men’s Shoes lead revenue contribution**, accounting for the largest share of total sales — indicating strong demand and scalability opportunity.
- **Sales accelerate toward the fourth quarter**, signaling seasonal shopping patterns suitable for promotional planning.
- **Top products show strong alignment between sales and review volumes**, confirming engagement influence on purchasing behavior.
- **Weekly sales patterns show consistent growth over time**, suggesting healthy product adoption and repeat purchase behavior.
- **High-performing categories such as Camera and Mobile Accessories demonstrate strong margin and should remain priority stocking areas.**

---

## Recommendations

Based on analysis, the following strategies are advised:

- **Strengthen category inventory planning** for top-performing segments such as Men’s Shoes and Camera equipment.
- **Leverage customer review behavior** with review-driven marketing and social proof to increase conversion rates.
- **Plan seasonal promotional strategies** aligned with end-of-year sales acceleration trends.
- **Prioritize advertising budgets toward top SKUs** demonstrating high growth and strong customer engagement.
- **Monitor emerging product segments** with rising review counts to support early-stage product investment decisions.

---

## Tools & Technologies

| Component | Technology Used |
|----------|----------------|
| Data Source | Excel Dataset |
| ETL & Cleaning | Power Query |
| Data Modeling | Power BI |
| Calculations | DAX |
| Visualization | Power BI Interactive Dashboard |
| User Interaction | Slicers, Drill-Through, Bookmarks, Conditional Formatting |

---

## Repository Includes

✔ `.pbix` Power BI file  
✔ Cleaned dataset  
✔ Dashboard screenshots  
✔ Full project documentation including insights and recommendations  

---

## Summary
This project demonstrates how retail product data can be transformed into actionable intelligence. The dashboard enables business teams to monitor performance, optimize product strategy, improve inventory decisions, and enhance customer engagement — all through data-driven insights.

---

