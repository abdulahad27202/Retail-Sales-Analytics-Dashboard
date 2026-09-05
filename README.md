# Retail Sales Analytics Dashboard

Analysis of 131,706 real retail transactions (Jan-Dec 2016) using Python and Power BI to uncover sales trends, customer behavior, and product performance.

## Data Source
Real point-of-sale scanner data — 131,706 transactions, 5,242 unique products, 22,625 customers.
[Kaggle: Retail Store Sales Transactions (Scanner Data)](https://www.kaggle.com/datasets/marian447/retail-store-sales-transactions)

## What this project does
- Cleaned and validated the dataset using Python (Pandas, NumPy) — confirmed zero duplicates/nulls, corrected date types
- Applied z-score analysis to flag 1,866 statistical outlier transactions (>3 standard deviations)
- Performed EDA: monthly sales trends, top-performing categories, customer spend distribution, day-of-week patterns
- Built an interactive Power BI dashboard with KPI cards, trend charts, category breakdown, and day-of-week analysis

## Key Findings
- **Friday is the peak sales day** ($295,344) — weekend sales drop over 65% from weekday levels
- Top customer spent **$3,986** across 62 transactions vs. a **$69.75** average
- **1,866 transactions (1.4%)** flagged as statistical outliers via z-score analysis
- Top 5 SKU categories account for a significant share of total revenue

## Tools
Python (Pandas, NumPy, Matplotlib), Power BI, Power Query, DAX

## Files
- `Retail_Sales_Dashboard.pbix` — Power BI dashboard
- `scanner_data_cleaned.csv` — cleaned dataset
- `monthly_sales_trend.png`, `top_categories.png`, `sales_by_day.png` — supporting charts from Python EDA
