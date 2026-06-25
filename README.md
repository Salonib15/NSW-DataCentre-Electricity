# NSW-DataCentre-Electricity
# Data Files

The raw data files are not included in this repository due to AEMO's
terms of use for electricity market data.

## To run the notebook you need two files:

### 1. NSW Price and Demand Data
- Filename expected: `NSW Price and Demand 20210701_20240630.xlsx`
- Source: AEMO Aggregated Data portal
- URL: https://www.aemo.com.au/energy-systems/electricity/national-electricity-market-nem/data-nem/aggregated-data
- Coverage: 1 July 2021 – 30 June 2024, NSW region, 5-minute intervals

### 2. Solar Farm Dispatch Data
- Filename expected: `Solar Farm Dispatch Data.xlsx`
- Source: Provided as part of BUSA8031 university assignment materials

Place both files in this `/data` folder and update the file paths
in Cell 3 of the notebook before running.

## About This Project

This was a major consulting project completed as part of my Master of 
Business Analytics at Macquarie Business School (BUSA8031, 2026).

Our team acted as consultants hired by an energy company to analyse 
what happens to NSW electricity prices and costs when large numbers of 
data centres are built across the state.

I was responsible for:
- Task 2 — building the price-impact regression model
- Task 4 — simulating and comparing all four procurement strategies
- NPV, Cash Flow at Risk, and payback analysis
- Forward cost projections from 2025 to 2030

All analysis was done in Python using real AEMO electricity market data
covering 315,646 five-minute intervals across FY2022–FY2024.
