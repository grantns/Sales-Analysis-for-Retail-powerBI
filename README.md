# Sales Analysis for Retail

## Table of Content

- [Project Overview](#project-overview)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results or Findings](#results-or-findings)
- [Recommendations](#recommendations)
 
### Project Overview
---

This project is a Retail Sales Analysis Dashboard built in Power BI. Its primary objective is to track, analyze, and visualize key performance indicators (KPIs) related to retail revenue, profitability, regional performance, and salesperson productivity over time (specifically covering the years 2022 to 2024).

The dashboard is structured into two main pages to balance high-level executive performance tracking with detailed operational insights.


**Page 1: Operational Performance & Sales Breakdown**
This page focuses on the operational drivers of the business, answering where, what, and who is generating revenue.
- **Salesperson Performance Table**: Tracks individual sales team members (Alice Brown, John Doe, Bob Johnson, Jane Smith) by units sold, total revenue, and total cost. Collectively, they generated $605,709.00 in Total Revenue against $483,034.00 in Total Cost.
- **Revenue by Store**: A horizontal bar chart comparing performance across physical locations, showing Store D as the top revenue generator, followed by Store B, Store C, and Store A.
- **Top 10 Products**: Analyzes inventory velocity by tracking the top-performing items by units sold, with Product 3 leading the list.
- **Sales by Product Category**: A pie chart breaking down sales distribution across four categories (A, B, C, and D). Revenue is distributed relatively evenly, with Category C leading slightly at 26.55% (291 units).
- **Revenue by Month**: An area chart showing continuous revenue tracking across the months, showing steady performance with a slight dip toward the end of the timeline (September).

  <img width="613" height="378" alt="sales-analysis for retail 1" src="https://github.com/user-attachments/assets/afe6c6b6-73e0-4dd2-9380-981f8418c9e2" />


**Page 2: Strategic Goals & Regional Performance**

This page serves as an executive summary, evaluating the company's performance against predefined targets and allowing for granular filtering.

- **Executive KPI Cards**:
  - Four high-level summary cards that measure performance against strategic targets:
- **Year Over Year (YoY)** 
- **Month Over Month (MoM)** 
- **Quarterly Revenue Analysis** 
- **Year To Date (YTD)** 
- **Profitability Tracking** 
- **Rolling 12 Months Revenue**:
    - A trend line chart mapping the "Sum of Revenue YTD" against the "Revenue Target" over a 12-month cycle, showing a gradual downward trend from January through April.
- **Interactive Slicers**: Dynamic filters that allow stakeholders to slice all dashboard data.

<img width="611" height="348" alt="sales analysis retail p2" src="https://github.com/user-attachments/assets/c23f55d3-eb05-411c-b972-84350d8d4025" />



### Tools
---
- Micosoft Excel
- Power BI

 ### Data Cleaning
---
Excel (Power Query) was used to clean and transform the raw data for this project. Power Query functions as an automated data pipeline, recording every cleaning action as a sequential step in a "recipe." This ensures that when new retail data is added, the entire cleaning process runs automatically at the click of a button.

The steps taken to clean the data included:
  1. Handling Missing and Null Values
  2. Standardizing Text and Case
  3. Data Type Formatting
  4. Splitting and Extracting Geographical Data
  5. Deduplication

### Exploratory Data Analysis
---
EDA questions that were asked to shape these two dashboard pages were:
1. What is our current financial position regarding total profitability?
2. Who are our top-performing sales professionals, and what is their primary driver of success—sales volume (units) or high-ticket value (revenue)?
3. How evenly is our sales volume distributed across our product categories, or are we dangerously reliant on a single category?
4. Which specific items are our absolute volume drivers, and which products populate our "Top 10" list?
5. Which physical store locations are generating the highest revenue, and which ones are underperforming and require operational support?
6. How do our sales metrics shift when we filter specifically for certain geographic territories or specific historical years?


### Results or Findings
---
1. Volume vs. Value Strategy Disparity Among Sales Staff:
   - An analysis of the salesperson performance table reveals a clear contrast in sales strategies. Jane Smith sold the highest volume of products (2,705 units) but generated the lowest total revenue ($145,520.00).
   - Alice Brown sold the lowest volume (2,551 units) but achieved the highest total revenue ($156,248.00). This indicates that Alice Brown is successfully pushing high-value
2. Highly Stable and Balanced Product Portfolio
   - The Sales by Product Category pie chart demonstrates a remarkably uniform distribution of sales volume across all four segments
   - Category C leads slightly at 26.55% (291 units), followed closely by Category D at 25.36%, Category A at 24.36%, and Category B at 23.72%.
3. Clear Revenue Hierarchy Among Retail Locations
   - The Revenue by Store bar chart outlines a distinct performance gap between individual physical branches.
   - Store D stands out as the primary revenue generator for the company, followed sequentially by Store B and Store C.
   - Store A lags significantly behind the others as the lowest-performing branch.
4. Short-Term Volatility vs. Long-Term Stagnation
   - The executive KPI cards on Page 2 highlight a conflict between short-term performance and annual growth.
  
### Recommendations
---
1. Optimize Store A’s Operational Performance
   - Conduct an operational audit on Store A to identify the root cause of the underperformance (e.g., poor foot traffic, local competitor pricing, or inventory mismatches).
  
2. Implement Strategic Sales Coaching & Incentive Alignment
   - Pair Jane and Alice for a peer-coaching initiative. Alice can train Jane on upselling techniques and pitching premium, high-margin items.
  
3. Leverage the Balanced Product Portfolio for Cross-Selling
   - Because no single product category dominates customer interest, implement cross-category bundling strategies. For example, create promotional packages that bundle a Category C item (the slight leader) with a slower-moving, high-margin item from Category B to increase the Average Order Value (AOV) without alienating any customer segment.


     

