E-commerce Sales & Performance Dashboard

**Project Overview**
This project establishes a robust, end-to-end data pipeline, starting with raw E-commerce sales data from Excel, transforming and analyzing it in MS SQL Server, and culminating in a dynamic Power BI Dashboard. The goal is to provide actionable insights into sales trends, customer behavior, product performance, and geographical revenue distribution, enabling stakeholders to optimize inventory, marketing spend, and supply chain logistics.

**Tools & Techniques Used**
1) Data Sourcing (MS Excel)- Initial Data Cleaning & Structuring (Removing duplicates, standardizing formats).
2) Data Transformation (SSMS) - ETL (Extract, Transform, Load)
3) Data Visualization (PowerBI)- Dashboard Creation, Power Query for data blending, DAX for calculated measures (Year-over-Year Growth). Use of KPI cards, trend lines (spark lines), donut charts, bar charts, and conditional formatting (green/red arrows) for immediate insight.

**Interactive Features**
**Filter Panel:** Slicers at the top allow users to dynamically filter the entire dashboard by: Year, Month, Segment.
**Dynamic KPIs:** All YTD metrics update based on the filters applied.
**Trend Indicators:** Immediate visual feedback (green up arrow / red down arrow) on YOY performance for key metrics and categories.

**Dashboard Highlights**
Key Performance Indicators (KPIs)

**YTD Sales: $11.50M (down 1.35% YOY)**
Interpretation: Sales are high but are slightly lagging the previous year's performance.

**YTD Profit: $1.33M (up 3.98% YOY)**
Interpretation: Profitability is growing despite the sales dip, suggesting improved efficiency or margins.

**YTD Quantity: 106.9K (down 7.81% YOY)**
Interpretation: A significant drop in units sold, consistent with the overall sales decline.

**YTD Profit %: 11.58% (up 5.41% YOY)**
Interpretation: The overall profit margin has improved healthily, indicating a positive shift in financial management.

**Insights by Category & Product**
Sales by Category:
Office Supplies leads with $6.90M in YTD Sales, but shows 1.71% YOY trend.
Furniture is performing flat with a $2.51M YTD Sales and a negligible YOY change (0.07%).
Technology is lagging significantly with $2.09M in sales and 1.85% YOY drop.
Top 5 Products by YTD Sales: Dominated by low-value office items like Staple envelope ($57K) and Staples ($52K).

**Geographical & Operational Insights**
Top 10 States by YTD Sales: California is the clear revenue leader at $2.3M.
Other strong contributors include New York ($1.3M) and Texas ($1.2M).

**Sales by Region:**
West and East are the primary revenue drivers, each contributing 28% ($3M).
Central and South contribute 32% ($4M) and 16% ($2M) respectively.

**Delivery Performance by Status:**
On Time deliveries are excellent at 54%.
Late deliveries are a significant operational challenge at 24%.

**Key Insights & Recommendations**

**Profitability vs. Volume:** While the business has successfully increased its Profit Margin and YTD Profit, the drop in YTD Quantity and YTD Sales indicates a potential issue with customer retention or new customer acquisition.

**Category Focus:** Office Supplies and Technology categories require immediate attention to reverse their negative YOY trends. A deep dive is needed to understand if this is due to competition or product lifecycle issues.

**Operational Improvement:** Late Delivery (24%) is a major area for improvement. Reducing late deliveries could positively impact customer satisfaction and potentially reduce order cancellations (18%).

**How to Use This Project**

Use the YEAR, MONTH, and SEGMENT filters to analyze performance over specific time frames or for targeted customer groups.
Focus on the YOY Trend columns in the 'Sales by category' table to prioritize which category needs immediate business intervention.
Compare the Top 10 States with the Sales by Region donut chart to formulate targeted regional marketing and inventory strategies.

