# ecommerce-etl-sqlite-dashboard
ecommerce_ETL_dashboard
# Task 14 – ETL Mini Pipeline

## Tools
- Python
- Pandas
- SQLite

## Dataset
- Ecommerce dataset (CSV)

## ETL Steps
1. Extracted raw CSV data
2. Cleaned missing values and duplicates
3. Standardized column names and datatypes
4. Created derived columns (profit_margin, segment flag)
5. Split data into customers, orders, products
6. Loaded outputs into CSV and SQLite database
7. Validated record counts

## Output Files
- processed/customers.csv
- processed/orders.csv
- processed/products.csv
- database.sqlite
