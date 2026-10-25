# SQL

No queries have been executed yet. Select the dataset and SQL engine first.

Suggested query sequence:

1. `01_data_quality.sql` — row counts, missing values, duplicates, and date coverage.
2. `02_sales_trends.sql` — sales by month using a documented sales definition.
3. `03_category_performance.sql` — category totals and shares, if categories exist.
4. `04_order_metrics.sql` — distinct orders and average order value, if order IDs exist.

For each query, document its purpose, inputs, assumptions, and validation. Reconcile SQL totals with Power BI before drawing conclusions.
