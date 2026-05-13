# BMW Global Sales Performance Dashboard

This repository contains an interactive Power BI project designed to track and analyze BMW's global sales performance from 2019 to 2023. The project integrates transactional data with visual assets to provide a comprehensive view of revenue trends, model popularity, and regional market penetration.

OUTPUT:

<img width="1329" height="749" alt="models" src="https://github.com/user-attachments/assets/af631352-90db-4727-82db-767aa617ef17" />
<img width="1330" height="741" alt="dashboard" src="https://github.com/user-attachments/assets/a0900542-c668-416d-ab09-84714b408063" />

## 🚀 Project Overview

The goal of this project is to provide a data-driven overview of BMW's sales lifecycle. By merging core sales metrics with external visual data (country flags and vehicle imagery), the dashboard offers an intuitive interface for stakeholders to identify growth opportunities and monitor dealer vs. online performance.

## 📁 File Descriptions

* **`BMW_dashboard.pbix`**: The primary Power BI Desktop file containing the data model, DAX measures, and interactive visualizations.
* **`BMW_Sales_Data.csv`**: The main dataset containing transactional records including Date, Model, Revenue, Quantity Sold, Region, Country, and Sales Channel.
* **`Car Images.csv`**: A helper file used to map BMW models to high-quality image URLs for dynamic visual headers within the report.
* **`Countries with Flags URL.csv`**: A geographic mapping file that provides flag icons and regional groupings (EMEA, APAC, LATAM, NA) for the global sales map.

## 📊 Key Insights & Features

* **Sales Trends (2019-2023):** Visualize yearly and monthly revenue growth across different series (X-series, M-series, i-electric).
* **Regional Performance:** Deep dive into sales by continent and specific countries using localized flag identifiers.
* **Channel Analysis:** Compare the efficiency of **Wholesale**, **Dealership**, and **Online** sales channels.
* **Product Deep-Dive:** Identify top-selling models by revenue and quantity to understand market demand.
* **Dynamic Imagery:** The dashboard uses the `Car Images.csv` to update visuals based on the selected vehicle model.

## 📈 Data Structure

The main sales table includes:

* **Date/Year:** Time-based analysis.
* **Model:** Specific BMW vehicle types (e.g., BMW i8, M5, X7).
* **Revenue/Quantity:** Core financial KPIs.
* **Geography:** Multi-level hierarchy (Region -> Country).
* **Channel:** Distribution method.


