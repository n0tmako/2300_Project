# 2300 Project: Retail Sales and Economic Downturns

This project tests whether U.S. retail spending drops during economic downturn years. We define a downturn year as a year in which annual inflation- and seasonally-adjusted Real Gross Domestic Product (`GDPCA`) has negative year-over-year growth.

## Research question

Do annual U.S. retail and food services sales decline in years when annual Real GDP declines?

The shared analysis window is 1992–2025, based on the overlap between:

- Census retail sales data from January 1992 through August 2026
- FRED annual Real Gross Domestic Product (`GDPCA`) from 1992 through 2025

The overlap should be filtered to complete/available retail years. Census months from 2026 may be partial (through August), and 2026 is not part of the GDP overlap.

## Data

1. **U.S. Census Bureau, Monthly Retail and Food Services Sales by Kind of Business**
   - Monthly time series for January 1992 through August 2026
   - Use the not-seasonally-adjusted or seasonally-adjusted series consistently
   - For this starter analysis, place the CSV in `data/` and identify the `Retail and food services sales, total` row
   - Values in the supplied Census file are in millions of dollars

2. **Federal Reserve Economic Data (FRED), Annual Real Gross Domestic Product**
   - Series: `GDPCA`
   - Annual observations from 1992 through 2025
   - Place the supplied `GDPCA.csv` in `data/`
