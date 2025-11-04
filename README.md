# Sales_Dashboard
## 1.Title
Sales Performance Dashboard – Region & Product Insights
## 2.Description
This dashboard presents a high-level overview of sales and profitability for the organisation. It highlights key performance indicators such as total sales, total profit, average sales per order, and average profit per order, and allows users to drill down by region, category, sub-category, state, and time period. The main views include:
•	KPI cards showing the summary metrics.
•	Pie charts showing sales distribution by region and by category.
•	Interactive map visualization showing sales by state and region.
•	Top 5 selling sub-categories (by sales) and top 5 profitable sub-categories (by profit).
•	Slicers/filters for region, category, sub-category, state and order date range.
The intention is to support decision-makers (sales managers, regional heads) to quickly identify where sales are strong, where profit is being generated, and which product lines and regions need focus.
## 3.Tech Stack
•	Visualization / BI tool: Microsoft Power BI (for building the dashboard, cards, map visuals and slicers)
•	Data transformation / ETL: Power Query (within Power BI) / possibly Excel/CSV import
•	Data modelling & measures: DAX (calculated measures such as Sum of Sales, Avg of Sales, Avg of Profit)
•	Data source & storage: Flat files (CSV/Excel) or relational database (e.g., Excel export from system, or SQL)
•	Hosting / Sharing: Power BI Service / Report Server (for sharing with stakeholders)
•	Additional tools: Excel (for raw data preparation), maybe GIS map visuals (if custom map)
## 4.Data Source
The dataset used underpins the dashboard and includes transactional sales data. Key features:
•	Each record corresponds to an order (with fields like order_date, region, state, category, sub_category, sales_amount, profit_amount).
•	Example fields used on the dashboard: Sales, Profit, Category, Sub-Category, Region, State, Order Date.
•	Data timeframe: from ~01 Feb 2019 to 29 Dec 2022 (per the date slicer visible in the screenshot).
•	Filters allow slicing by region, category, sub-category, state and date range.
•	The “Count of Sales” KPI (9,994) suggests there were ~9,994 orders in the dataset.
## 5.Highlights & Key Insights
•	Total Sales ~ 2.30 M and Total Profit ~ 286.40 K (via the KPI-cards) give a snapshot of overall business scale.
•	Average Sales per order ~ 229.86, Average Profit per order ~ 28.66 — useful for setting benchmarks or comparing segments.
•	Sales distribution by region (pie chart) shows that e.g. one region (West) accounts for ~31.6% of sales, while others vary around 17%-30% (visualised).
•	Sales distribution by product category: categories such as Technology, Furniture, Office Supplies have approximately equal shares (~31-36%) — signalling balanced product mix or opportunity for focus.
•	Map visual shows geographic spread of sales by state/region — helpful to identify hotspots or under-performing states.
•	Top 5 selling sub-categories (by sales): e.g., Phones (~0.33M), Chairs (~0.33M), Storage (~0.22M), Tables (~0.21M), Binders (~0.20M) — this signals high volume lines.
•	Top 5 profitable sub-categories (by profit): e.g., Copiers (~56 K), Phones (~45 K), Accessories (~42 K), Paper (~34 K), Binders (~30 K) — helpful to compare profit vs sales and highlight high margin lines.
## 6.Screenshots
https://github.com/Nayemsyed/Sales_Dashboard/blob/main/screenshot_of_sales_dashboard.png
