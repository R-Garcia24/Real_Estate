# Real Estate Transaction Analysis (2001–2022)

This project analyzes over 1 million real estate sales in Connecticut from 2001 to 2022 using Python, SQL (SQLite), and Tableau.

## Objective

The goal of this project is to:
- Explore real estate trends across towns and property types
- Simulate missing financial metrics using realistic assumptions
- Identify market opportunities using Cap Rate and Price per Square Foot
- Communicate insights visually through an interactive dashboard

## Tools Used

- Python (pandas, NumPy, SQLite3)
- Jupyter Notebook
- Tableau Public
- Git & GitHub

## Data Source

- [Connecticut Real Estate Sales (2001–2022)](https://data.ct.gov/Housing-and-Development/Real-Estate-Sales-2001-2022-GL/5mzw-sjtu) — over 1 million property records

## Key Metrics Created

The original dataset lacked certain investment-related fields. These were engineered in Python to support analysis:

- **Estimated Net Operating Income (NOI)**: Simulated as 7% of the sale price
- **Cap Rate**: Estimated NOI divided by sale price
- **Square Footage**: Simulated using typical ranges by property type
- **Price per SqFt**: Sale price divided by simulated square footage

## SQL Analysis (via SQLite in Jupyter)

Queries were executed using SQLite within Jupyter to:
- Rank towns by total sales volume and average price per SqFt
- Compute average Cap Rate by property type
- Analyze market performance and compare segments

## Tableau Dashboard

An interactive dashboard was created in Tableau Public to visualize:
- **Top 10 Towns by Price per SqFt**
- **Average Cap Rate by Property Type**
- Insight callouts and business interpretation


## Key Findings

- Willington and Greenwich lead in price per square foot, suggesting high-value markets
- Commercial properties offer the highest average Cap Rate, making them strong candidates for return-focused investment
- Public Utility and Apartment assets show lower Cap Rates, indicating greater stability but reduced profitability

## Author

**Raul Garcia**  
Data Intelligence and AI | Transaction Analytics  
[LinkedIn](https://linkedin.com/in/raul-garcia-27a14519b) | [GitHub](https://github.com/R-Garcia24)


