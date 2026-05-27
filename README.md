# Regional Sales Performance Dashboard | Power BI

## Project Overview
Interactive Power BI dashboard for regional sales performance tracking, 
revenue analysis, and business decision-making across product categories and regions.

## Dashboard Preview
![Dashboard](dashboard-screenshot.png)

## Key KPIs Tracked
- Total Revenue: 825K
- Total Profit: 142K
- Total Orders: 20
- Average Order Value: 41.25K

## Features
- Region-wise Revenue Analysis (South, East, West, North)
- Monthly Revenue Trend tracking
- Category-wise Revenue breakdown (Electronics, Furniture)
- Product-wise Sales Distribution (Laptop, Mobile, Sofa)
- Interactive Slicers — Region, Category, Customer filters
- Dynamic KPI cards with DAX measures

## Tools Used
- Power BI Desktop (DAX, Slicers, KPI Cards, Charts)
- Excel (Data Source — Regional Sales Data)

## DAX Measures Used
- Total Revenue = SUM(Sales[Revenue])
- Total Profit = SUM(Sales[Profit])
- Average Order Value = DIVIDE([Total Revenue], [Total Orders])

## Business Insights
- Electronics category drives highest revenue
- South region leads in overall sales performance
- Laptop contributes 43.52% of total product sales
