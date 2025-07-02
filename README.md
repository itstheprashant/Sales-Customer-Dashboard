# Sales & Customer Insights Dashboards

[**Live Demo**](https://public.tableau.com/views/DynamicSalesCustomerDashboards_17502374374380/SalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

This project consists of two interactive Tableau dashboards — **Sales Dashboard** and **Customer Dashboard** — designed to provide business stakeholders with data-driven insights on sales performance and customer behavior.

## Project Overview

### Purpose
- Enable **executives and sales managers** to track yearly performance.
- Support **marketing and strategy teams** with detailed customer behavior analysis.
- Deliver **data visualizations** for KPIs, trends, top customers, and category-level performance.

---

## Dashboards Overview

### Sales Dashboard

![Sales Dashboard](https://github.com/itstheprashant/Sales-Customer-Dashboard/blob/f037e111254617bc58cd1977a64727e4ab26b7ed/images/Sales%20Dashboard.png)

#### Features:
- **KPI Summary**: Total Sales, Profit, and Quantity for Current Year vs. Previous Year.
- **Monthly Trends**: Visual comparison of KPIs across months.
- **Subcategory Breakdown**: Sales + Profit/Loss by subcategories for Current & Previous Year.
- **Weekly Trends**: Highlight sales and profit above/below weekly average.

---

### Customer Dashboard

![Customer Dashboard](https://github.com/itstheprashant/Sales-Customer-Dashboard/blob/f037e111254617bc58cd1977a64727e4ab26b7ed/images/Customer%20Dashboard.png)

#### Features:
- **KPI Summary**: Total Customers, Sales per Customer, and Orders for Current Year vs. Previous Year.
- **Monthly Customer Trends**: Track metrics with monthly highs and lows.
- **Customer Order Distribution**: Histogram to show customer loyalty/engagement.
- **Top 10 Customers by Profit**: Profit, Sales, Last Order Date, Rank, and Number of Orders.

---

## Data Filters Panel

<h3 align="center">Filters Panel</h3>
<div align="center">
  <img src="https://github.com/itstheprashant/Sales-Customer-Dashboard/blob/f037e111254617bc58cd1977a64727e4ab26b7ed/images/Data%20Filters.png" 
       alt="Filters Panel" 
       width="30%" 
       height="50%"/>
</div>

Filters are available to customize dashboard views dynamically:

- **Year Selector**
- **Product**:
  - Category
  - Sub-category
- **Location**:
  - Region
  - State
  - City

---

## Data Source

![Data Source Model](https://github.com/itstheprashant/Sales-Customer-Dashboard/blob/f037e111254617bc58cd1977a64727e4ab26b7ed/images/Data%20Source.png)

The data source integrates multiple CSV files:

- `Orders.csv` — contains order-level details.
- `Customers.csv` — customer metadata.
- `Products.csv` — product category and subcategory info.
- `Location.csv` — mapping for region, state, and city.

---

## 📌 Key Technologies

- **Tableau** for dashboard development
- **CSV** datasets as data sources
- **Calculated fields**, **parameters**, and **filters** for interactivity

---

## Navigation

Users can switch between dashboards with clickable icons and interact directly with charts to filter data across views.

---

## Conclusion

- The dashboards provide a **comprehensive overview of sales and customer metrics**, allowing stakeholders to make informed, data-driven decisions.
- **Dynamic visualizations** enable users to analyze year-over-year performance, identify sales trends, and monitor customer engagement effectively.
- **Flexible filtering options** (by year, category, sub-category, region, state, city) make exploration easy and tailored to user needs.
- Supports strategic planning by highlighting **top-performing customers**, product subcategories, and critical time periods (monthly/weekly).
- Designed for **ease of use and interactivity**, enabling business users with no technical background to derive actionable insights.

These dashboards bridge the gap between raw data and business strategy, driving operational efficiency and customer-focused decisions.

