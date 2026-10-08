# BrewBean Coffee Shop Sales Analytics

## Project workflow
1. Clean and validate raw inventory data.
2. Summarize the cleaned data using pivot tables.
3. Present the results through dashboards and KPI cards.

## Repository structure
- `data/raw/`: Original source workbook.
- `data/cleaned/`: Cleaned/validated workbook used for analysis.
- `analysis/`: Pivot-table summaries and analysis notes.
- `dashboard/`: Dashboard workbook or exported dashboard images.
- `presentation/`: Presentation slides and speaking notes.

## Dataset
The workbook contains 500 outlet-product inventory records covering 10 outlets and 50 products.

## Main calculations
- Closing Stock = Opening Stock + Received Stock - Units Sold - Wastage
- Stock Utilization = Units Sold / (Opening Stock + Received Stock)
- Reorder Required when Closing Stock <= Reorder Level

## Current deliverable
The Excel workbook includes data-cleaning checks, pivot-style summaries, dashboard KPI cards, and charts.
