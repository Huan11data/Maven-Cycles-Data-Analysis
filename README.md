# Maven-Cycles-Data-Analysis
## Project Overview
At the request of stakeholders, a comprehensive analysis of Maven Cycles’ sales data was conducted to develop an executive dashboard highlighting key business performance metrics. The analysis focused on revenue, profit, total orders, product category comparisons, top-selling products, regional sales trends, and actionable insights to inform strategic decision-making.

## Executive Summary
This report analyzes Maven Cycles’ sales data to assess revenue trends, profit margins, customer behavior, and product effectiveness. The findings guide actionable strategies for streamlining inventory, refining customer targeting, and prioritizing high-performing geographic markets

## Data Source
The dataset was sourced from MavenAnalytics.io and included transactional sales records, product details, and regional data.

## Data Preparation & Cleaning
## 1.	Integration & Initial Checks

o	Consolidated multiple tables using Power Query.

o	Conducted initial quality assurance checks by reviewing column profiles, addressing errors, and removing duplicates and blank entries.

## 2.	Enhancing Granularity

o	Added date hierarchies (Year, Quarter, Month, Week) to enable time-based drill-down analysis.

o	Established a star schema model with 1:M relationships between fact and dimension tables for optimized query performance.

## Analysis & Key Metrics

Developed DAX measures for critical KPIs:

o	Total Sales, Total Orders, Total Profit, Profit Margin, and dynamic calculations for period-over-period comparisons.

Analyzed trends across product categories, regions, and timeframes to identify growth opportunities and underperforming segments.

An interactive executive dashboard was designed to visualize insights:
1.	Performance Overview:
o	Key metrics (Revenue, Profit, Orders) displayed as dynamic KPIs.
o	Line chart illustrating profit trends over time.
2.	Product Analysis:
o	Matrix table ranking top-performing products by sales volume, revenue, and margin.
o	Donut chart breaking down revenue distribution across product subcategories.
3.	Regional Insights:
o	Geographic map highlighting sales by region.
o	Slicers enable users to filter data by region, product category, and timeframe.


 
