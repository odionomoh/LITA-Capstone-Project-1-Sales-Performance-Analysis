# LITA-Capstone-Project-1-Sales-Performance-Analysis

# Project title: Retail Sales Analysis

[Project Overview](#project-overview)

Tools Used

Key Findings

Excel Analysis

SQL Analysis

Power BI Analysis

[Featured Projects](#featured-projects)

Detailed Analysis of Retail Sales Performance

Top-Selling Products

Regional Sales Performance

Monthly Sales Trends

Recommendations

Next Steps

Dashboard

Files

---
## Project Overview

Analyzing sales performance of a retail store to uncover key insights.

## Tools Used

* Excel for data cleaning and transformation
* SQL for data extraction
* Power BI for data visualization

## Key Findings

* Top-selling products
* Regional sales performance
* Monthly sales trends


## Excel Analysis

## Sales Performance Dashboard

- Created using Excel pivot tables and charts to visualize sales trends.
- Includes:
    - Top-selling products
    - Regional sales breakdown
    - Monthly sales trends
 
## Key Excel Functions Used

- SUMIFS for conditional summing
- AVERAGEIFS for conditional averaging
- PIVOTTABLES for data summarization
- CHARTS for data visualization

## Formula Usage and Applications

- Used SUMIFS to calculate total sales by region and product category.
- Applied AVERAGEIFS to determine average monthly sales by product.
- Created pivot tables to summarize sales data by quarter and region.
- Designed charts to visualize top-selling products and monthly sales trends.


## SQL Analysis

## Database Query Overview

Conducted SQL queries to extract and analyze sales data from the database.

## Key Queries

- Sales by product category
- Top-selling products by region
- Monthly sales performance
- Regional sales breakdown

## Key SQL Concepts Used

- SELECT statements
- JOIN clauses
- GROUP BY and HAVING
- SUBQUERIES
- AGGREGATE functions (SUM, AVG, COUNT)

## Example Queries

``` Query 1:
SELECT 
    [Product], 
    SUM([Sales_Amount]) AS TotalSales
FROM 
    [Tablename]
GROUP BY 
    [Product]
ORDER BY 
    TotalSales DESC;
```

``` Query 2:
SELECT TOP 1 
   [Product],
    SUM([Sales_Amount]) AS TotalSalesValue
```


## Power BI Analysis

Power BI Dashboard

Created interactive and dynamic dashboards using Power BI to visualize sales trends and insights.

## Key Visualizations

- Top-selling products by region
- Monthly sales performance
- Regional sales breakdown
- Product category sales comparison

## Key Power BI Features Used

- Data Modeling
- DAX Formulas
- Visualization Best Practices
- Interactive Filtering

## Example Usage

- Used Power BI to create a sales performance dashboard with drill-down capabilities.
- Implemented DAX formulas to calculate year-over-year sales growth.
- Designed visualizations to showcase top-selling products by region.
- Applied interactive filtering to enable dynamic exploration.

---


### Featured Projects:

## Detailed Analysis of Retail Sales Performance
### Top-Selling Products Analysis

## Dataset Overview
- Total Sales Revenue: ₦10,587,500
- Number of Products: 6
- Sales Period: 2023-2024

## Ranking and Sales Revenue

1. Shoes: ₦3,087,500 (29.16% of total sales)
2. Shirts: ₦2,450,000 (23.14% of total sales)
3. Hats: ₦1,585,500 (15.00% of total sales)
4. Gloves: ₦1,500,000 (14.17% of total sales)
5. Jackets: ₦1,050,000 (9.92% of total sales)
6. Socks: ₦912,000 (8.62% of total sales)

## Key Insights

1. Shoes and Shirts dominate sales: These two products account for 52.28% of total sales revenue.
2. Hats and Gloves show strong performance: These products contribute 29.17% to total sales revenue.
3. Jackets and Socks have room for growth: These products account for 18.54% of total sales revenue.

## Product Category Analysis

- Apparel: Shoes, Shirts, Hats, Gloves, Jackets (84.22% of total sales)
- Accessories: Socks (8.62% of total sales)

## Recommendations

1. Increase Shoe and Shirt inventory: Meet growing demand and capitalize on popularity.
2. Promote Hats and Gloves: Targeted marketing campaigns to maintain momentum.
3. Enhance Jacket and Sock offerings: Improve designs, quality, or pricing to boost sales.
4. Explore new product categories: Consider complementary products to diversify revenue streams.

## Actionable Steps

1. Analyze customer demographics and preferences.
2. Monitor inventory levels and optimize restocking.
3. Develop targeted marketing campaigns.
4. Conduct competitor analysis.

## Future Outlook

- Continue monitoring sales trends and customer feedback.
- Adjust product offerings and marketing strategies accordingly.
- Explore opportunities for growth and expansion.
---

### Regional Sales Performance Analysis

Total Sales: ₦10,587,500 million

## Regional Breakdown:

1. South Region: ₦4,675,000 million (44.1% of total sales)
2. East Region: ₦2,450,000 million (23.1% of total sales)
3. North Region: ₦1,950,000 million (18.4% of total sales)
4. West Region: ₦1,512,500 million (14.3% of total sales)

## Key Insights:

1. South Region Dominance: The South Region accounts for nearly half of total sales, indicating strong market presence and customer demand.
2. Regional Imbalance: Significant sales disparities exist between regions, suggesting opportunities for growth in underperforming areas.
3. East and North Regions Potential: These regions contribute substantially to overall revenue, indicating potential for expansion.

## Regional Sales Comparison:

| Region    | Sales (₦ million) | % of Total Sales |
|-----------|------------------|------------------|
| South     | 4,675,000        | 44.1%            |
| East      | 2,450,000        | 23.1%            |
| North     | 1,950,000        | 18.4%            |
| West      | 1,512,500        | 14.3%            |
|-----------|------------------|------------------|
| Total     | 10,587,500       | 100%             |

## Growth Opportunities:

1. West Region: Invest in targeted marketing campaigns to bridge the sales gap.
2. North Region: Enhance distribution channels and customer engagement.
3. East Region: Expand product offerings and optimize sales strategies.

## Regional Sales Ranking:

1. South
2. East
3. North
4. West

## Recommendations:

1. Conduct regional market research to understand customer preferences.
2. Analyze sales channels and distribution networks.
3. Develop tailored marketing strategies for underperforming regions.

## Actionable Steps:

1. Identify regional customer segments and preferences.
2. Optimize product offerings and pricing strategies.
3. Monitor regional sales performance regularly.
---

### Monthly Sales Trends
## 2023 Sales Performance

- Total Sales: ₦5,575,000
- Highest Sales Months:
    1. February: ₦1,250,000
    2. July: ₦1,200,000
    3. October: ₦675,000
- Lowest Sales Months:
    1. April: ₦37,500
    2. August: ₦150,000
    3. September: ₦175,000
- Average Monthly Sales: ₦463,750
- Sales Growth Rate: 17.5% (from January to December)
- Quarterly Sales:
    1. Q1: ₦812,500 (14.6% of total)
    2. Q2: ₦837,500 (15% of total)
    3. Q3: ₦1,625,000 (29.2% of total)
    4. Q4: ₦1,300,000 (23.3% of total)
- Seasonal Patterns:
    1. Peak sales in Q3 (July-September)
    2. Low sales in Q2 (April-June), particularly in April

## 2024 Sales Performance (January-August)

- Total Sales: ₦5,012,500
- Highest Sales Months:
    1. February: ₦1,500,000
    2. January: ₦1,000,000
    3. August: ₦875,000
- Lowest Sales Months:
    1. April: ₦200,000
    2. July: ₦187,500
    3. March: ₦275,000
- Average Monthly Sales: ₦625,312.5
- Sales Growth Rate: -10.2% (from January to August, compared to same period in 2023)
- Quarterly Sales:
    1. Q1: ₦2,775,000 (55.3% of total)
    2. Q2: ₦1,175,000 (23.4% of total)
    3. Q3: ₦1,062,500 (21.2% of total)

## Comparison to 2023

- Decrease in total sales (-10.2%)
- Shift in peak sales from Q3 (2023) to Q1 (2024)

## Recommendations

1. Investigate factors contributing to decreased sales in 2024: Identify underlying causes of the decline.
2. Analyze reasons for low sales in April: Understand factors affecting April sales performance.
3. Leverage Q3 peak sales momentum (2023): Apply strategies from successful Q3 months.
4. Monitor Q4 sales to identify potential year-end trends: Track sales performance closely.
5. Adjust marketing strategies to capitalize on Q1 growth (2024): Optimize marketing efforts for Q1.

## Additional Insights

- The significant decline in sales growth rate (-10.2%) warrants immediate attention.
- The shift in peak sales from Q3 to Q1 indicates changing market trends.
- Q2 sales decline in 2024 (-23.4% compared to Q2 2023) requires analysis.

## Actionable Steps

1. Conduct thorough sales data analysis.
2. Identify and address underlying causes of sales fluctuations.
3. Develop targeted marketing campaigns.
4. Monitor sales performance closely.

  
## Dashboard
![Top Perfoming Product](https://github.com/user-attachments/assets/59cba8a6-d44c-4e23-b9db-240164ce1eb6)


![Regional Breakdown](https://github.com/user-attachments/assets/763f87d0-8a6c-44e6-97a8-53251ab9beb6)


![Monthly Sales Trend](https://github.com/user-attachments/assets/e2a028c9-0c24-470a-9fff-adae7e7fae9f)


## Files

* `SalesData.xlsx`[Download here](https://docs.google.com/spreadsheets/d/1xpPZfdFjBwxz6qgZIBjoKZ3FTyNQc26L/edit?usp=drive_link&ouid=100692561819122818038&rtpof=true&sd=true): Raw sales data
* `SalesQueries.sql`[Download here](https://drive.google.com/file/d/1yzC2ckfsxbJ0X5wXwSbJZ7wCvlLNyQoo/view?usp=drive_link): SQL queries for data extraction
* `SalesDashboard.pbix`[Download here](https://drive.google.com/file/d/1-3d4krRiMRTx7xatO1Y2rxlPQ85KK_Hf/view?usp=drive_link): Power BI dashboard file


FROM 
    [Tablename]
GROUP BY 
    [Product]
ORDER BY 
    TotalSalesValue DESC;
```
