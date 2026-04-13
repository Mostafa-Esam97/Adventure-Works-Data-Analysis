# Adventure Works: Business Intelligence Executive Report

## 📊 Project Overview
This project involves a comprehensive Business Intelligence solution for **Adventure Works**, a global manufacturing company. The goal was to transform raw sales, product, and customer data into an interactive executive dashboard to track performance and identify growth opportunities across various regions including North America, Europe, and the Pacific.

## 🚀 Key Performance Indicators (KPIs)
* **Total Revenue:** $24.9M.
* **Total Profit:** $10.5M.
* **Total Orders:** 25.2K.
* **Return Rate:** 2.17%.

## 🛠️ Technical Workflow

### 1. Data Transformation (Power Query)
* Cleaned and shaped raw datasets to ensure data integrity for reporting.
* Managed data types and established consistent naming conventions for product and customer records.

### 2. Data Modeling
* Implemented a **Snowflake Schema** to connect Fact tables with normalized Dimension tables.
* Developed a complex relationship structure to handle hierarchical data across products, subcategories, and categories.

### 3. DAX Analysis
* Developed custom **DAX measures** for complex calculations including Total Revenue and Total Profit.
* **Time Intelligence:** Analyzed Revenue and Order trends over time from 2020 through 2022.
* **What-if Analysis:** Created a "Price Adjustment" parameter to forecast how profit shifts based on percentage changes.

### 4. Interactive Visualizations
* **Executive Summary:** High-level view of revenue trends and product category orders.
* **Customer Deep-Dive:** Segmented 17.4K unique customers by income level and occupation.
* **Product Performance:** Monitored specific product metrics, such as the Water Bottle (30 oz.) orders versus targets.
* **Map Integration:** Visualized global sales distribution using Azure-backed mapping.

## 🧰 Tools Used
* **Power BI Desktop** (Data Visualization & DAX).
* **Power Query** (ETL Process).
* **Data Source:** Adventure Works Raw Datasets.

---

### 💡 How to use this repository
1. Download the `.pbix` file from the repository.
2. Open it in **Power BI Desktop** to explore interactive elements like the "Product Metric Selection" and "Price Adjustment" sliders.
