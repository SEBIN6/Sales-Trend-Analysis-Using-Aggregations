# ClassicModels Analysis

This repository contains SQL queries to analyze monthly revenue and order volume using the `classicmodels` database in MySQL.

## Files
- `analysis.sql`: SQL queries to:
  - Extract month from `orderDate`.
  - Group by year and month.
  - Calculate revenue using `SUM(quantityOrdered * priceEach)`.
  - Count distinct orders for volume.
  - Sort results by year and month.
- `results.csv`: Output of the final analysis (monthly revenue and order volume, 2003–2005).
- `mysqlsampledatabase.sql`: Database schema and data (optional).

