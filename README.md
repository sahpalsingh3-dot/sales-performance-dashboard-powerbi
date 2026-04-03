# Sales Performance Dashboard (Power BI)

## Project Overview
This project analyzes sales performance across regions and time using Power BI. The goal is to monitor KPI performance, identify top- and low-performing regions, and track monthly sales trends using interactive visuals.

## Business Goal
Help decision-makers answer:
- Are sales meeting targets?
- Which regions and categories drive performance?
- How are sales trending over time?
- Is month-over-month growth improving or declining?

## Tools Used
- Power BI
- DAX
- Data Modeling
- Time Intelligence

## Data Model
- Fact table: sales_project_dataset
- Dimension table: DateTable
- Relationship: DateTable[Date] → sales_project_dataset[Order Date]

## Key Features
- KPI cards: Total Sales, Total Target, Achievement %, Performance Status
- Region analysis with contribution % and ranking
- Product/category breakdown
- Time analysis with YTD and MoM Growth
- Interactive slicers for Region, Year, Month, Segment, and Category

## Key Insights
- Sales show fluctuating trends across months.
- Several months exhibit negative month-over-month growth.
- YTD sales continue to increase despite short-term volatility.
- Electronics is the strongest revenue-driving category.
- Regional performance varies, with contribution and ranking visible on the overview page.

## Dashboard Preview

### Overview Page
![Overview](overview.png)

### Trend Analysis Page
![Trend](trend.png)

## Files
- Sales_Analysis_Dashboard.pbix
- overview.png
- trend.png
