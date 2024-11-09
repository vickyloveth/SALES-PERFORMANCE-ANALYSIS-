# SALES-PERFORMANCE-ANALYSIS-
Analyzing sales performances for a retail store.

## Table  of content
- Overview
- Dataset
- Tools used
- Analysis and Findings
- Insights and Recommendations.

### Overview

This project analyzes the sales performance of a retail store using Excel, SQL, and Power BI. The goal is to uncover key insights and create an interactive dashboard highlighting top-selling products, regional performance, and monthly sales trends.

### Dataset

Sales data containing the following columns:

    - orderid (unique identifier)
    - customerid (unique customer identifier)
    - product (product name)
    - region (geographic region)
    - quantity (number of units sold)
    - unitprice (price per unit)
    - Revenue (total revenue per order)


### Tools Used

- Power Bi
- Excel
- SQL


#### Power BI Dashboard

The dashboard includes the following visualizations:

1. Top-Selling Products by Revenue (Stacked column Chart)
2. Total sales by Products (pie Chart)
3. Monthly Sales Trends (Line Chart)
5. Total Revenue by Region (Donut Chart)
6. Total no of customers (cards)
7. Total Revenue (cards)
8. Average sales by Products (Table)
9. Total quantity sold


![Screenshot (34)](https://github.com/user-attachments/assets/8b125f69-1daa-4253-a6ea-876ffac99f79)



#### Excel Analysis

Sales_data.xlsx: Excel file containing:
    - Data filtering and sorting
    
   ![Screenshot (33)](https://github.com/user-attachments/assets/6c31fd49-0364-4d03-ae6f-53b15bdec946)

    
  - Pivot tables for regional and product analysis and Charts for visualizing trends
    
    ![Screenshot (30)](https://github.com/user-attachments/assets/3647a778-5963-4b59-95cf-d947d3e3f94b)

  ![Screenshot (32)](https://github.com/user-attachments/assets/8af8212d-d6dc-4e8b-96fe-9c33580a2690)


#### SQL Queries

- sales_queries.sql: SQL file containing:
    - Queries for data extraction and filtering
    - Aggregate functions for revenue and quantity calculations

     
  ![Screenshot (37)](https://github.com/user-attachments/assets/10ceb0eb-3016-4dbd-a79c-aac088b46371)


  ![Screenshot (38)](https://github.com/user-attachments/assets/51861d36-2ccb-4a5f-a09d-341ef6a8702e)



### Analysis and Findings

Top-Selling Products

-  Products by revenue:
    1. Shoes (#613,380k)
    2. Shirts (#485,600k)
    3. Hat (#316,175k)
    4. gloves (#296,900k)
    5. Jackets (#208,230k)
    6. Sock (#180,785k)
 
      
- Products by quantity sold:
    1. Hats (15,929 units)
    2. Shoes (14,402 units)
    3. Shirts (12,388 units)
    4. Gloves (12,369 units)
    5. socks (7,921 units)
    6. Jackets (5,452 units)
 
   Regional Performance

- Top 2 regions by revenue:
    1. South (#927,820)
    2. East (#485,925)
      
- Bottom 2 regions by revenue:
    1. north (#387,000)
    2. Midwest (#300,345)
  

 Monthly Sales Trends

- Peak sales months: February and June 
- Lowest sales months: April and september


 
  

      

### Insights and Recommendations

Product Insights

1. Shoes dominate revenue: 31% (#613,380k) despite lower unit sales (14,402).
2. Hats lead unit sales: 15,929 units, but lower revenue (#316,175k).
3. Gloves and shirts balance: Similar unit sales (12,388/12,369), moderate revenue.

Regional Insights

1. South drives revenue: 51% (#927,820).
2. East supports growth: 27% (#485,925).
3. North and west underperform: 22% and 17% respectively.

Monthly Sales Trends

1. February and June peaks: Capitalize on holiday/summer demand.
2. April and September dips: Adjust inventory, promotions.

Recommendations

1. Diversify South region marketing: Maintain momentum.
2. Enhance East region offerings: Increase revenue share.
3. Improve North/Midwest presence: Targeted marketing, partnerships.
4. Optimize inventory: Align with peak months (February, June).
5. Promotions during low-sales months: Boost April, September sales.
6. Upsell/cross-sell: Shoes, hats, gloves.
7. Monitor seasonal influences: Adjust strategies.    
