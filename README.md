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

## <a href="https://github.com/Huan11data/Maven-Cycles-Data-Analysis/blob/main/Maven%20Cycles%20Dashboard.png"> Executive Dashboard</a>  

## 1.	Performance Overview
   
o	Key metrics (Revenue, Profit, Orders) displayed as dynamic KPIs.

o	Line chart illustrating profit trends over time.

## 2.	Product Analysis

o	Matrix table ranking top-performing products by sales volume, revenue, and margin.

o	Donut chart breaking down revenue distribution across product subcategories.

## 3. Regional Insights
o	Geographic map highlighting sales by region.

o	Slicers enable users to filter data by region, product category, and product subcategory.

## Key Insights & Recommendations
## 1.	Regional Revenue Concentration

o	Insight: North America generates 41% of total revenue, outperforming Australia (28%) and Europe (23%).

o	Actions:

	Expand targeted marketing in Europe and Australia to replicate North America’s success.

	Analyze regional customer preferences to tailor promotions and inventory.

## 2.	Product Category Imbalance

o	Insight: Bikes and Accessories drive 95% of revenue, while Clothing lags at 5%.

o	Actions:

	Prioritize high-margin bikes/accessories (e.g., bundles, premium models).

	Reassess the Clothing category: survey customers or adjust pricing/design to boost appeal.

## 3.	Profit Margin Opportunities

o	Insight: Top 3 products deliver 65% profit margins (vs. company average of ~50%).

o	Actions:

	Promote top products aggressively to maximize profitability.

	Audit low-margin items to reduce costs or discontinue underperformers

## Conclusion
The dashboard equips stakeholders with a user-friendly tool to monitor performance, identify trends, and make data-driven decisions. Notable findings include seasonality in high-margin product sales and untapped growth potential in specific regions, providing actionable recommendations for resource allocation and inventory planning.





 
