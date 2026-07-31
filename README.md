# Sales Performance Analytics Dashboard

Interactive Power BI dashboard analyzing sales revenue and quantity across customers, markets, and products. Built to help sales and business teams quickly identify top/bottom performers, spot trends, and support data-driven decision-making.

## 📊 Overview

This dashboard consolidates sales transaction data into a single, interactive view — replacing manual spreadsheet reporting with a dynamic, filterable Power BI report covering revenue and sales volume across customers, markets, and products over time.

## 🗂️ Data Model

| Table | Description |
|---|---|
| `sales customers` | Customer-level details (customer_name) |
| `sales markets` | Market/region-level details (markets_name) |
| `sales products` | Product-level details (product_code) |
| `sales date` | Calendar attributes (year, cy_date) for time-based analysis |
| `BaseMeasures` | Dedicated table holding core DAX measures |

## 📈 Key Metrics (DAX Measures)

- **Revenue**
- **Sales Qty**

## 📄 Report Layout

A single-page dashboard including:
- KPI cards summarizing total **Revenue** and **Sales Qty**
- Bar charts breaking down performance by **market**, **product**, and **customer**
- A **revenue trend line chart** tracking performance over time
- **Year** and **market** slicers for dynamic filtering across the entire report

## 🎯 Business Objective

Enable sales leadership to:
- Identify top- and bottom-performing markets, products, and customers
- Spot revenue trends and seasonality over time
- Compare performance across regions and time periods without manual data wrangling
- Maintain a single source of truth for sales performance tracking

## 🛠️ Tools Used

- **Power BI** — data modeling, DAX, report/dashboard design

```

## 📌 Skills Demonstrated

- Relational/star-schema data modeling
- DAX measure design (Revenue, Sales Qty)
- Interactive Power BI report building (slicers, KPI cards, trend charts)
- Sales performance analysis across markets, products, and customers
