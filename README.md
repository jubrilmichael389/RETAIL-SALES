# E-Commerce Retail Sales Dashboard – Power BI

An interactive *Power BI dashboard* for analyzing e-commerce retail sales performance.  
This project cleans, transforms, and visualizes an e-commerce dataset to uncover insights into sales trends, brand performance, category distribution, geographic sales, discounts, ratings, stock levels, and more.

![Dashboard Overview 1](images/dashboard_overview_1.png)

## Project Overview

This dashboard helps stakeholders monitor key retail metrics:
- Total delivery days, revenue (total price), top brands, units sold, and ratings
- Performance breakdown by *brand*, *category*, *city*, *seller*, *payment method*, and *month*
- Discount impact, product ratings, and color-based scoring

Built with *Power BI Desktop* using data cleaning in *Power Query* and DAX calculations for dynamic measures.

## Dashboard Highlights

*Key KPIs (at a glance):*
- Total Delivery Days: *481K*
- Total Price (Revenue): *₹2.41 Billion*
- Most Common Brand: *Puma*
- Total Units Sold: *201 Million*
- Total Ratings/Reviews: *320K+*

*Main Visuals Include:*
- Delivery days by brand (horizontal bar)
- Total price by category (clustered column)
- Total price trend by month (line/area chart)
- Delivery days by payment method
- Total discount % by category (donut chart)
- Total price by city (bar chart)
- Brand performance by ratings
- Product score by category and color

![Dashboard Overview 2](images/dashboard_overview_2.png)

Slicers/filters for:
- Brand
- Category

## Data Source & Preparation

*Raw data*: Excel file containing ~20 sample records (product_id, name, category, brand, seller, city, price, discount %, final price, rating, reviews, stock, units sold, listing date, etc.)

*Cleaning & Transformation steps (Power Query):*
- Promoted headers
- Changed column data types
- Removed unnecessary columns
- Filtered out blank/invalid rows (multiple steps)
- Added calculated column: *Month Name* using Date.MonthName([listing_date])

![Power Query Editor – Adding Month Name](images/power_query_month_name.png)

*Sample raw data preview (Excel):*

![Excel Data Preview](images/excel_data_preview.png)

## Tools & Technologies

- *Power BI Desktop* (data modeling, DAX, visuals)
- *Power Query* (ETL – extract, transform, load)
- *DAX* (measures for aggregations, KPIs, dynamic calculations)
- *Excel* (source data)

## How to Use / Explore the Dashboard

1. Download or clone this repository
2. Open the .pbix file in *Power BI Desktop*
   - (If you upload the .pbix file to this repo, users can directly open it)
3. Interact with slicers (Brand, Category) to filter visuals dynamically
4. Hover over charts for tooltips and cross-highlighting
