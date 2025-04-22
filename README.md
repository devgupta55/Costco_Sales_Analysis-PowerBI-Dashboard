# Costco_Sales_Analysis-PowerBI-Dashboard
## 📌 Project Overview
This repository contains a Power BI dashboard designed to analyze Costco key business metrics from 2020 to 2024. The dashboard provides insights into key performance indicators (KPIs) such as total revenue, total profit, and total quantity sold, along with detailed breakdowns by region, product, and customer segment.

## <img src="https://github.com/microsoft/PowerBI-Icons/blob/main/SVG/Power-BI.svg" width="24" style="margin-bottom: -10 px"> Costco Sales Power BI Dashboard
<img src="https://github.com/user-attachments/assets/2144eb65-9d30-4307-856d-4a13b241d8e3">

## 📋 Key Features

-   **Interactive Visualizations:** Dynamic charts and graphs allow users to explore sales trends and patterns.
-   **KPI Monitoring:** Track total revenue, profit, and quantity with year-over-year comparisons.
-   **Regional Analysis:** Examine sales performance across different regions (South, East, West, Central).
-   **Product Performance:** Identify top-selling products and their contribution to total sales and profit.
-   **Customer Segmentation:** Analyze revenue by customer segments (Home Office, Corporate, Consumer).
-   **Time-Series Analysis:** Review monthly sales trends and compare them against revenue targets.
-   **Geospatial Analysis:** Interactive map highlighting sales distribution across different states.

## 📅 Data Model

The data model consists of five tables, designed for efficient analysis and reporting:

-   **Product:** Contains information about products, including category, sub-category, product ID, product name, cost of goods sold (COGS), profit, and unit price.
-   **Customers:** Contains customer details such as city, country, customer ID, customer name, postal code, region, segment, and state.
-   **Orders:** Includes order-related data like cost of goods sold (COGS), customer ID, discount, net sales, order date, order ID, product ID, profit, and quantity.
-   **Date_Table:** A date dimension table with fields for Date, Month Start Date, Quarter, and Year, facilitating time-based analysis.
-   **MeasuresTable:** A table containing various DAX measures used for calculations, including Value, KPI Profit YoY, KPI Quantity YoY, KPI Revenue YoY, Prev Year Revenue.

### 📌 Relationships

The tables are related as follows:

-   One-to-many relationship between **Product** and **Orders** using `product_id`.
-   One-to-many relationship between **Customers** and **Orders** using `customer_id`.
-   One-to-many relationship between **Date_Table** and **Orders** using `order_date`.

### ✏️ Data Model Diagram
<img src="https://github.com/user-attachments/assets/2666cee8-e417-4b88-893a-c5a55e24a4e9" width="600" alt="Costco DataModel">

## 📈 Key Insights from Analysis

The dashboard includes the following key visualizations:

-   **KPI Cards:** Display total revenue (\$355.39K), total profit (\$205.30K), and total quantity (23K) with year-over-year comparisons.
-   **Sales Trend Chart:** A line chart showing total revenue and revenue target trends over time (Jan 2024 - Nov 2024).
-   **Orders vs. Target:** A gauge chart indicating the number of orders (3047) against a target.
-   **Revenue by Segment:** A donut chart breaking down total revenue by customer segments (Home Office, Corporate, Consumer).
-   **Regional Sales Bar Chart:** Horizontal bar chart showing total revenue and total profit by region (South, East, West, Central).
-   **Top Products Table:** A table listing the top products by sales, profit, quantity, and orders.
-   **Geographic Heatmap:** A map visualizing sales distribution across different states.

## 🛠️ Technologies Used

-   **Power BI:** Data visualization and dashboard creation.
-   **DAX:** Data Analysis Expressions for creating custom measures and calculations.

## ⚙️ Setup Instructions

1.  Download the Power BI file (`.pbix`) from this repository.
2.  Open the file in Power BI Desktop.
3.  Explore the interactive dashboard and gain insights into the Costco sales data.

## 📌 Conclusion
The Costco Sales Data Analytics project provides valuable insights into sales performance, customer preferences, and product demand. The findings can help businesses optimize inventory, target high-value customer segments, and improve sales strategies.

This project serves as a powerful analytical tool for data-driven decision-making in retail sales.

