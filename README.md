# E-Commerce Retail Sales Dashboard – Power BI

An interactive *Power BI dashboard* for analyzing e-commerce retail sales performance.  
This project cleans, transforms, and visualizes an e-commerce dataset to uncover insights into sales trends, brand performance, category distribution, geographic sales, discounts, ratings, stock levels, and more.


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


*Sample raw data preview (Excel):*


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


<img width="1920" height="1080" alt="Screenshot 2026-03-03 183450" src="https://github.com/user-attachments/assets/41eb06ee-3512-4189-b088-02659102b05e" />
<img width="1920" height="1080" alt="Screenshot 2026-03-03 183558" src="https://github.com/user-attachments/assets/efb667c3-ad47-4508-a71b-63c74f67bd4b" />
<img width="1920" height="1080" alt="Screenshot 2026-03-03 183701" src="https://github.com/user-attachments/assets/69a515cb-d0f7-42eb-9a46-e913f8e87371" />
<img width="1920" height="1080" alt="Screenshot 2026-03-03 183723" src="https://github.com/user-attachments/assets/15a70451-3fcf-4e21-81f9-1742862fc04e" />

Created by Jubril Michael
Email: jubrilmichael389@gmail.com
