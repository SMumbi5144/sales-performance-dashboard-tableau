# Sales Performance Dashboard — Tableau

An interactive dual-dashboard built in Tableau Public to help sales managers 
and executives analyse year-over-year sales performance, customer behaviour, 
and product profitability across regions and subcategories.

## Live Dashboard
- [Sales Dashboard](https://public.tableau.com/views/sales-performance-dashboard_17829834166370/SalesDashboard)
- [Customer Dashboard](https://public.tableau.com/views/sales-performance-dashboard_17829834166370/CustomerDashboard)
- 
- >Screenshots below show 2023 data. The dashboards are fully dynamic and support any year from 2020 to 2023-visit the live links above to expore other years
- ![Sales Dashboard](Sales%20Dashboard.png)
- ![Customers Dashboard](Customer%20Dashboard.png)

## Project Overview
**Business Problem:** Sales managers and executives lacked a centralised, 
interactive view of sales performance. Data was spread across multiple tables 
with no easy way to compare years, identify trends, or make fast 
data-driven decisions.

**Solution:** A dynamic dual-dashboard in Tableau Public allowing users to 
filter by year, product category/subcategory, and location , with seamless 
navigation between Sales and Customer views.

## Tools & Skills
- Tableau Public
- Data modelling (star schema)
- Calculated fields & parameters
- Dashboard design & interactivity

## Dataset
- Source: Data with Baraa (Superstore-style sales dataset)
- Period: 2020–2023
- Tables: Orders (fact), Customers, Products, Location

## Dashboard Features

### Sales Dashboard
- KPI BANs: Total Sales ($733K ▲20.4%), Total Profits ($93K ▲14.2%), 
  Total Quantity (12K ▲26.8%) vs previous year
- Sparkline charts with highest/lowest month indicators
- Bar-in-bar subcategory comparison (CY Sales vs PY Sales + Profit/Loss)
- Weekly Sales & Profit trends with above/below average highlights
- Dynamic year parameter: select any year from 2020–2023

### Customer Dashboard
- KPI BANs: Total Customers (693 ▲8.6%), Sales Per Customer ($1,058 ▲10.8%), 
  Total Orders (1,687 ▲28.3%) vs previous year
- Customer Distribution histogram by number of orders
- Top 10 Customers by Profit table (rank, last order, profit, sales, orders)
- Interactive filters by category, subcategory, region, state, city

## Key Insights
- Phones drove the highest sales across all subcategories
- Tables and Machines generated losses despite high sales volumes
- Most customers placed only 1–2 orders, suggesting retention opportunity
- Sales grew 20.4% YoY while profit grew only 14.2% — margin worth investigating
- Orders grew 28.3% YoY, outpacing customer growth (8.6%) — existing 
  customers are ordering more

## Project Workflow
1. Analysed user requirements & drew mockups
2. Built star schema data model in Tableau
3. Created calculated fields for CY/PY metrics and % differences
4. Built and formatted all charts
5. Assembled dashboards with containers, filters, and navigation

## Author
Stacy Mumbi | [GitHub](https://github.com/SMumbi5144)


