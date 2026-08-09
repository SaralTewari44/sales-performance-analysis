# Global Economic Analysis — World Bank API

This project uses the World Bank API (via the `wbgapi` Python package) to analyze 20 years (2004–2023) of macroeconomic and development data across 266 economies.

## Objectives

- Compare GDP per capita (PPP) trends across world regions
- Identify the fastest-growing and slowest-growing economies by average GDP growth
- Examine the relationship between government education spending and unemployment
- Track global and regional unemployment trends over time
- Explore the relationship between government health spending and life expectancy

## Tools & Methods

- Python
- `wbgapi` (official World Bank API client)
- pandas, numpy
- matplotlib
- Data cleaning, merging, and grouping across multiple World Bank indicators

## Key Findings

- Guyana, Ethiopia, and Turkmenistan had the highest average GDP growth from 2004–2023, while Syria, Yemen, and Sudan had the weakest
- Higher government health spending as a share of GDP is generally associated with higher life expectancy, though with a wide spread within each spending tier
- Unemployment trends vary substantially by region, with no single global pattern over the two-decade window

## Files

- `sales_performance_analysis.ipynb` – Main analysis notebook covering GDP, growth, unemployment, education spending, and life expectancy

## About

Analysis of 20 years of World Bank economic and development data across 266 economies using the World Bank API.
