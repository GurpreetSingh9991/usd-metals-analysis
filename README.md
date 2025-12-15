# Impact of USD Movements on Copper & Iron Prices

## Project Overview
This project analyzes how movements in the US Dollar Index (DXY) impact industrial metal prices, specifically Copper and Iron. The analysis focuses on returns, volatility, and time-varying correlations to better understand macro-driven market behavior.

## Data
- Daily historical price data for:
  - Copper
  - Iron
  - US Dollar Index (DXY)
- Time period: 2023–2024

## Methodology
- Cleaned and standardized price data using Python (Pandas)
- Calculated:
  - Daily returns
  - Rolling volatility (20-day, 60-day)
  - 60-day rolling correlation with DXY
- Used SQL (SQLite) to segment USD regimes (strengthening vs weakening) and compare average metal returns
- Built interactive Power BI dashboards for visualization

## Key Insights
- The relationship between USD and industrial metals is time-varying rather than static
- Periods of USD strengthening are associated with weaker metal returns and increased volatility
- Rolling correlation analysis highlights regime-dependent behavior in macro-driven markets

## Tools Used
- Python (Pandas, NumPy)
- SQL (SQLite)
- Power BI

## Visuals
Screenshots of Power BI dashboards and analysis outputs are included in the repository.

## Author
Gurpreet Singh
