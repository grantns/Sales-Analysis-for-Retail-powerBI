# Sales Analysis for Retail

### Project Overview

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
- Micosoft Excel
- Power BI

 ### Data Cleaning

Excel (Power Query) was used to clean and transform the raw data for this project. Power Query functions as an automated data pipeline, recording every cleaning action as a sequential step in a "recipe." This ensures that when new retail data is added, the entire cleaning process runs automatically at the click of a button.

The steps taken to clean the data included:
  1. Handling Missing and Null Values
  2. Standardizing Text and Case
  3. Data Type Formatting
  4. Splitting and Extracting Geographical Data
  5. Deduplication

### Exploratory Data Analysis

