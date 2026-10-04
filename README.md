# BrewMetrics BI

A version-controlled Business Intelligence solution for BrewMetrics Coffee Co. built using Power BI, GitHub, and GitHub Copilot.

## Project Overview

BrewMetrics BI analyzes coffee sales across cities, store formats, product categories, and dates. The dashboard helps management understand sales trends, city-level performance, and the seasonal behavior of Cold Brew.

## Data Model

The project uses a star schema:

- **Fact_Sales** – transaction-level sales data including date, city, item, quantity, unit price, and sales amount.
- **Dim_Date** – date, month, quarter, and year information.
- **Dim_City** – city information.
- **Dim_Product** – product category and item information.

## DAX Measures

1. MoM Sales Growth
2. Running Total Sales
3. Target Attainment %
4. Item Sales Rank

## Dashboard Insights

- Sales vary significantly across the April–June period, showing noticeable changes over time.
- The cities have different sales performance levels, allowing management to identify stronger and weaker markets.
- Cold Brew sales show a visible seasonal pattern across the reporting period.

## Tools Used

- Power BI Desktop
- Power BI Project (.pbip)
- GitHub
- GitHub Copilot
- Visual Studio Code# BrewMetrics BI

A version-controlled Business Intelligence solution for analyzing BrewMetrics Coffee Co. sales data.
