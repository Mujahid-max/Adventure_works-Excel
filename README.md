# Sales Analysis Project 📊🚀

![Dashboard preview](https://github.com/Mujahid-max/Adventure_works-Excel/blob/115c32301bf3c106750156be0d063a78e2c7905e/Screenshot%202025-01-09%20002616.png)

This project involves analyzing the attached sales data to extract actionable insights. Below are the steps performed, along with the desired outputs.

---

## Table of Contents 🔗
1. [Union of Fact Internet Sales](#1-union-of-fact-internet-sales)
2. [Data Enrichment with Lookups](#2-data-enrichment-with-lookups)
3. [Date Field Calculations](#3-date-field-calculations)
4. [Derived Metrics](#4-derived-metrics)
5. [Visualizations](#5-visualizations)
6. [KPIs and Dashboards](#6-kpis-and-dashboards)

---

### 1. Union of Fact Internet Sales ➕
Combine **Fact Internet Sales** and **Fact Internet Sales New** to create a unified dataset for analysis.

---

### 2. Data Enrichment with Lookups 📃
- Lookup **Product Name** from the `Product` sheet.
- Lookup **Customer Full Name** from the `Customer` sheet.
- Lookup **Unit Price** from the `Product` sheet.

---

### 3. Date Field Calculations 🕒
From the `OrderDateKey` field, calculate the following:
- **Year** (e.g., 2024)
- **Month No** (e.g., 1 for January)
- **Month Full Name** (e.g., January, February)
- **Quarter** (Q1, Q2, Q3, Q4)
- **YearMonth** (Format: YYYY-MMM, e.g., 2024-Jan)
- **Weekday No** (e.g., 1 for Monday)
- **Weekday Name** (e.g., Monday, Tuesday)
- **Financial Month** (adjusted to fiscal year starting in April)
- **Financial Quarter** (aligned with fiscal year quarters)

---

### 4. Derived Metrics 📊
- **Sales Amount** = `(Unit Price × Order Quantity) - (Unit Price × Unit Discount)`
- **Production Cost** = `Unit Cost × Order Quantity`
- **Profit** = `Sales Amount - Production Cost`

---

### 5. Visualizations 🔼
1. **Pivot Table**:
   - Show **Month** vs **Sales**, with **Year** as a filter.

2. **Bar Chart**:
   - Display **Year-wise Sales**.

3. **Line Chart**:
   - Display **Month-wise Sales**.

4. **Pie Chart**:
   - Show **Quarter-wise Sales** distribution.

5. **Combination Chart**:
   - Plot **Sales Amount (Bar)** and **Production Cost (Line)** together.

---

### 6. KPIs and Dashboards 🎯📈
Create KPIs and additional visualizations for the following:
- **Performance by Products**:
  - Sales by product categories and top-selling products.
- **Performance by Customers**:
  - Top customers by sales and profit.
- **Performance by Region**:
  - Sales and profit by geographic region.

---

### Final Dashboards 🔄
- Integrate all insights into interactive dashboards to visualize trends and key metrics effectively. Use slicers and filters for dynamic exploration.

---

### How to Use 🔧
1. Import the Excel data into your preferred BI tool (Excel, Power BI, etc.).
2. Follow the steps outlined above to replicate the analysis.
3. Explore the visualizations and dashboards for insights.

---

### Contributing 🛠️
Feel free to submit issues or pull requests for enhancements or bug fixes.

---

