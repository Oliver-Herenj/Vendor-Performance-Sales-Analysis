# Vendor-Performance-Sales-Analysis

## Project Overview
This project analyzes vendor purchase and sales data to uncover insights into profitability, inventory efficiency, and supplier performance. The goal was to transform raw transactional data into actionable business intelligence to guide strategic decision-making in procurement, sales, and inventory management.

## Tech Stack
- **Programming Language:** Python
- **Database & Tools:** SQL, SQLite, SQLAlchemy
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Key Concepts:** ETL, Data Cleaning, SQL Querying, Statistical Analysis, Data Visualization

## Data Sources
The analysis integrates multiple data tables:
- `purchases`: Vendor purchase orders with quantities and costs.
- `sales`: Sales transactions with quantities and revenue.
- `vendor_invoice`: Invoice details including freight costs.
- `purchase_prices`: Standard product pricing.

## Project Steps
1. **Data Ingestion & Cleaning:** Built an ETL pipeline in Python to load and clean CSV data into a SQLite database.
2. **Data Modeling:** Engineered a master `vendor_sales_summary` table using complex SQL queries (CTEs, Joins, Aggregations) to combine key metrics.
3. **Exploratory Data Analysis (EDA):** Analyzed sales trends, profit margins, and inventory turnover.
4. **Statistical Analysis:** Performed hypothesis testing to compare profit margins between high and low-performing vendors.
5. **Insight Generation:** Delivered data-driven recommendations for business optimization.

## Key Insights
- Identified **$2.71 million** in locked inventory due to slow-moving stock.
- Discovered bulk purchasing leads to **72% lower unit costs**.
- Found **198 high-margin, low-sale brands** ideal for targeted promotions.
- Determined that the top 10 vendors represent **65% of total purchases**, indicating high supply chain risk.
- Statistically confirmed that low-volume vendors have **significantly higher profit margins** than top-volume vendors.

## Files
- ` vendor_sales_summary.csv` 
- `Vendor Performance Analysis.ipynb` 
- `README.md` – Project documentation
