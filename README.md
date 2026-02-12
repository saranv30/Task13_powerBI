# Task 13: BI Dashboard Storytelling – KPI Report  
**Elevate Labs Data Analyst Internship**

![Power BI Logo](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)  
![Global Superstore](https://img.shields.io/badge/Dataset-Global%20Superstore-blue?style=for-the-badge)

## Project Overview
This repository contains my submission for **Task 13** of the Elevate Labs Data Analyst Internship program.  

I built an **executive-ready KPI dashboard** using **Power BI Desktop** to analyze sales performance of the **Global Superstore** dataset. The dashboard highlights key metrics (Sales, Profit, Margin), trends, category & region breakdowns, top products, and interactive filters.

Goal: Provide clear, actionable insights for business decision-makers.

## Tools & Technologies Used
- **Primary Tool**: Power BI Desktop (free version)
- **Dataset**: Global Superstore (commonly used retail sales sample dataset)
- **Other**: Notepad (for insights text file), GitHub for submission

## Key Features of the Dashboard
1. **KPI Cards** (top section)  
   - Total Sales  
   - Total Profit  
   - Profit Margin (%)

2. **Trend Chart**  
   - Sales over time (monthly/yearly line chart)

3. **Category Breakdown**  
   - Bar chart showing sales by product category

4. **Region Performance**  
   - Bar chart / Map view of sales & profit by region

5. **Top 10 Products**  
   - Table listing highest-selling products

6. **Interactive Slicers**  
   - Filters for Region, Date (Order Date), and Category

7. **Insights Text Box**  
   - 3 key business findings based on data analysis

## Files in this Repository
| File Name                  | Description                                      |
|----------------------------|--------------------------------------------------|
| `dashboard.pbix`           | Complete Power BI file (main deliverable)        |
| `dashboard_export.pdf`     | Exported dashboard as PDF (static view)          |
| `insights_task13.txt`      | Text file with 3 key insights/findings           |
| `Global_Superstore.csv`    | Dataset used (if you want to include it)         |
| `README.md`                | This file – project documentation                |
| (Optional) Screenshots/    | Folder with dashboard preview images (add if you want) |

## How to View the Dashboard
1. Download the `.pbix` file.
2. Open it in **Power BI Desktop** (free download: https://powerbi.microsoft.com/desktop/).
3. Interact with slicers and visuals.
4. For static view → open `dashboard_export.pdf`.

## Key Insights (Summary)
(These are examples — replace with your actual findings from the data)

1. **Technology category** contributes the highest sales volume, but **Furniture** has the lowest profit margin — potential area for pricing or cost optimization.
2. **Central & West regions** show consistent strong performance; focus marketing efforts on **South & East** to improve overall profitability.
3. Sales peaked in **Q4 (October–December)** each year — likely due to holiday season; plan inventory and promotions accordingly.

Full detailed insights are in `insights_task13.txt`.

## What I Learned
- Creating DAX measures (SUM, DIVIDE for margin)
- Designing clean, executive-friendly layouts
- Using slicers for interactivity
- Avoiding misleading visuals (consistent scales, proper labeling)
- Validating totals against raw data

## Interview-Ready Notes
- **Effective dashboard**: Clear, focused, interactive, mobile-friendly, tells a story.
- **KPI**: Key Performance Indicator — e.g., Total Sales, Profit Margin.
- **Drill-down vs Filter**: Drill-down explores hierarchy (e.g., year → month); filter applies globally.
- **Avoid misleading visuals**: Use same axis scales, show full data range, label properly.
- **Validate totals**: Cross-check measure sums with Excel pivot or raw data aggregation.
