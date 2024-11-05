# LITA-Capstone-Project-1-Sales-Performance-Analysis

# Project title: Retail Sales Analysis

[Project Overview](#project-overview)

Tools Used

Key Findings

[Featured Projects](#featured-projects)

Detailed Analysis of Retail Sales Performance

Top-Selling Products

Regional Sales Performance

Monthly Sales Trends

Recommendations

Next Steps

Dashboard


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


### Featured Projects:
---

## Detailed Analysis of Retail Sales Performance
### Top-Selling Products

* Shoes: ₦3 million
* Shirts: ₦2.4 million

### Regional Sales Performance

* South Region: ₦4.6 million
* East Region: ₦2.4 million

### Monthly Sales Trends

* February 2023: ₦1.2 million (increase)
* February 2024: -₦1.5 million (decrease)

## Recommendations

1. **Product Strategy**: Focus on Shoes and Shirts.
2. **Regional Focus**: Prioritize the South Region.
3. **Seasonal Analysis**: Investigate February's sales fluctuations.

## Next Steps

* Visualize data for better understanding.
* Analyze sales drivers and obstacles.```
  
## Dashboard
![Top Perfoming Product](https://github.com/user-attachments/assets/59cba8a6-d44c-4e23-b9db-240164ce1eb6)


![Regional Breakdown](https://github.com/user-attachments/assets/763f87d0-8a6c-44e6-97a8-53251ab9beb6)


![Monthly Sales Trend](https://github.com/user-attachments/assets/e2a028c9-0c24-470a-9fff-adae7e7fae9f)


## Files

* `SalesData.xlsx`[Download here](https://docs.google.com/spreadsheets/d/1xpPZfdFjBwxz6qgZIBjoKZ3FTyNQc26L/edit?usp=drive_link&ouid=100692561819122818038&rtpof=true&sd=true): Raw sales data
* `SalesQueries.sql`[Download here](https://drive.google.com/file/d/1yzC2ckfsxbJ0X5wXwSbJZ7wCvlLNyQoo/view?usp=drive_link): SQL queries for data extraction
* `SalesDashboard.pbix`[Download here](https://drive.google.com/file/d/1-3d4krRiMRTx7xatO1Y2rxlPQ85KK_Hf/view?usp=drive_link): Power BI dashboard file

### Database Query

### Description
``` Query 1: SELECT 
    [Product], 
    SUM([Sales_Amount]) AS TotalSales
FROM 
    [Tablename]
GROUP BY 
    [Product]
ORDER BY 
    TotalSales DESC;
```

``` Query 2: SELECT TOP 1 
   [Product],
    SUM([Sales_Amount]) AS TotalSalesValue
FROM 
    [Tablename]
GROUP BY 
    [Product]
ORDER BY 
    TotalSalesValue DESC;
```
