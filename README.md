# Global Superstore Sales Data Analysis and Visualization with Power BI

## Project Overview
This project involves a comprehensive analysis and visualization of global superstore sales data using Power BI. The objective is to gain insights into sales trends, performance metrics, and business market's behavior through an interactive dashboard.

## Key Objectives
- Connect Power BI to the sales database.
- Analyze tables and relationships for a coherent data model.
- Clean and transform data to prepare for visualization.
- Build an interactive dashboard for detailed insights and reporting.

## Key Features
- Sales Metrics Overview: Summarizes key metrics such as total sales, order quantity, average delivery days, and number of returned orders.
- Sales Segmentation: Analysis by business category segment and market segments to understand revenue sources.
- Top and Bottom Products: Displays best-selling and least profitable products to inform stocking and marketing decisions.
- Regional Sales: Maps sales distribution across global regions to highlight strong and weak markets.

## Methodology

### 1. Project Setup
Database Connection: Connected Power BI to the Global Superstore database, containing transactional data on customers, orders, products, and regions.
Tables and Relationships: Defined relationships between key tables (Orders, Customers, Products, and Regions) to ensure accurate data modeling.

### 2. Data Cleaning and Transformation
Power Query Editor: Cleaned and transformed data by removing duplicates, null values, and standardizing column names.
Added a new column named Year by extracting the year from the order date field. Also created a Delivery Days column to calculate the time taken to deliver each order, based on the order and shipping dates in the dataset.   

### 3. Data Visualization
- **Sales Overview:** Provided insights on total sales, quantity sold, average delivery days, and returned orders.
- **Sales by Segment:** Analyzed revenue distribution across Consumer, Corporate, and Home Office segments.
- **Sales by Market:** Breakdown of sales performance by regions (Asia Pacific, Europe, USCA, LATAM, and Africa), highlighting key markets.
- **Sales by Region (Map):** Visualized geographical sales patterns with a focus on North America and Europe.
- **Top Products:** Identified best-sellers (e.g., Cisco and Motorola Smart Phones) for inventory and promotion planning.
- **Loss and Profit Analysis by Product:** Analyzed losses (e.g., Cubify Cubes) and profits (e.g., Canon Imaging Products) to optimize product strategies.

## Usage and Installation

1. Clone the Repository:
2. Open Power BI File:
- Launch Power BI Desktop.
- Open PowerBI_Project.pbix to access the full dashboard and data model.
