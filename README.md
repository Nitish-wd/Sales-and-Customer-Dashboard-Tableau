# 📊 Sales & Customer Dashboards (Tableau)

Two interactive Tableau dashboards analyzing sales performance and customer behavior, built on the Superstore dataset (2020–2023), with dynamic year-over-year comparisons.

## 📈 About the Project
This project includes two linked dashboards:

1. **Sales Dashboard** — tracks Sales, Profit, and Quantity with year-over-year % change, a sub-category performance comparison, and weekly sales trends.
2. **Customer Dashboard** — tracks total Customers, Sales per Customer, and Orders with year-over-year % change, customer distribution, and top customers.

Both dashboards use a **dynamic year selector parameter**, so all KPIs and charts update instantly when a different year is chosen — no need to rebuild separate views per year.

## 🗂️ Dataset
Built on the Superstore dataset:
- **9,994 orders** across **793 customers**
- Fields: Order Date, Ship Date, Ship Mode, Segment, Category, Sub-Category, Sales, Quantity, Discount, Profit, Region, State, City
- Date range: 2020–2023

## 🔍 Key Calculations
- Current Year vs. Previous Year values for Sales, Profit, Quantity, Customers, Orders, and Sales per Customer
- Percentage difference (YoY) calculated fields for each KPI
- Dynamic parameter-driven year selection

## 📊 Dashboards

**Sales Dashboard**
- KPI cards: Sales, Profit, Quantity (with YoY % change)
- Sub-Category performance comparison
- Weekly sales trend chart

**Customer Dashboard**
- KPI cards: Customers, Sales per Customer, Orders (with YoY % change)
- Customer distribution chart
- Top customers chart

## 🛠️ Tools Used
Tableau — Calculated Fields, Parameters, KPI Cards, Dashboard Actions

## 📁 File
`Sales & Customer Dashboards (Dynamic).twbx` — packaged Tableau workbook, open with Tableau Desktop or Tableau Public.
