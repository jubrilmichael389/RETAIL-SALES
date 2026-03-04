# E-Commerce Retail Sales Dashboard & Data Analysis

*Interactive Power BI dashboard + data cleaning pipeline* for analyzing an Indian e-commerce retail dataset (~20–50K+ products).

This repository contains:
- Cleaned and transformed *e-commerce retail dataset* (Excel source)
- *Power Query* transformation steps (including month name extraction, blank row removal, filtering, type changes, etc.)
- Fully built *Power BI Desktop dashboard* visualizing key retail performance metrics

## Dashboard Highlights

### KPIs (Cards)
- Total Delivery Days: *481K*
- Total Price (Revenue proxy): *₹2.41 Billion*
- Most Common Brand: *Puma*
- Total Units Sold: *201 Million*
- Total Ratings/Reviews: *320K+*

### Key Visuals
- *Delivery days by Brand* (highest: LG, Apple, Prestige, Philips, etc.)
- *Total Price by Category* (Beauty, Toys, Fashion, Sports, Electronics leading)
- *Total Price trend by Month* (seasonal pattern visible — peaks in Mar, Oct–Nov)
- *Delivery days by Payment Method* (UPI/CARD, CARD/Wallet, COD variants dominant)
- *Total Discount by Category* (donut chart)
- *Total Price by City* (Delhi slightly leads, followed by Pune, Chennai, Hyderabad, etc.)
- *Brand performance by average rating / score*
- *Product score by Category & Colour* (Silver, Black, Gold consistently high)

### Slicers / Interactivity
- Brand
- Category
- Seller city (implicit through visuals)

## Data Preparation (Power Query)
- Removed blank/invalid rows
- Promoted headers
- Changed column data types
- Filtered inconsistent/out-of-range rows (multiple filter steps)
- Added calculated column: *Month Name* (Date.MonthName([listing_date]))
- Removed unnecessary columns

## Tools Used
- Microsoft Excel
- Power Query (M language)
- Power BI Desktop
- DAX (for measures & calculated columns in visuals)

## Purpose
Great starter / intermediate project for:
- Power BI dashboard development
- Retail / e-commerce analytics
- Data cleaning & transformation in Power Query
- Visual storytelling with KPIs, trends, geographic & categorical breakdowns
 Hover over charts for tooltips and cross-highlighting


<img width="1920" height="1080" alt="Screenshot 2026-03-03 183450" src="https://github.com/user-attachments/assets/41eb06ee-3512-4189-b088-02659102b05e" />
<img width="1920" height="1080" alt="Screenshot 2026-03-03 183558" src="https://github.com/user-attachments/assets/efb667c3-ad47-4508-a71b-63c74f67bd4b" />
<img width="1920" height="1080" alt="Screenshot 2026-03-03 183701" src="https://github.com/user-attachments/assets/69a515cb-d0f7-42eb-9a46-e913f8e87371" />
<img width="1920" height="1080" alt="Screenshot 2026-03-03 183723" src="https://github.com/user-attachments/assets/15a70451-3fcf-4e21-81f9-1742862fc04e" />

Created by Jubril Michael
Email: jubrilmichael389@gmail.com
