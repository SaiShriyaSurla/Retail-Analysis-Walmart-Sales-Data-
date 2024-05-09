# Retail Analysis with Walmart Data

## Project Overview
This project aims to enhance predictive analytics for Walmart's sales, focusing on the impact of holidays and economic conditions. Utilizing historical sales data from 45 Walmart stores, this project addresses the challenges posed by unexpected demand fluctuations and stock shortages.

## Dataset Description
The dataset spans sales data from February 5, 2010, to November 1, 2012, and includes the following fields:
- **Store**: Identifier for the store.
- **Date**: The week of the sales.
- **Weekly_Sales**: Sales figures for the given week.
- **Holiday_Flag**: Indicator for holiday weeks (`1` for holiday, `0` for non-holiday).
- **Temperature**: Temperature on the day of sale.
- **Fuel_Price**: Cost of fuel in the region.
- **CPI**: Consumer Price Index.
- **Unemployment**: Unemployment rate.

### Key Holidays
- **Super Bowl**
- **Labour Day**
- **Thanksgiving**
- **Christmas**

## Analysis Tasks
1. Identify the store with the maximum sales.
2. Determine the store with the most significant sales variability and its coefficient of variation.
3. Analyze quarterly growth rates for Q3 2012.
4. Investigate the impact of holidays on sales compared to non-holiday periods.
5. Provide a detailed monthly and semester view of sales.

## Statistical Model
For Store 1:
- **Linear Regression**: Predict future demand based on economic indicators such as CPI, unemployment rate, and fuel prices. Date variables are restructured for analysis.
- **Date Transformation**: Convert dates into days to analyze daily sales impacts.

## Requirements
- Python 3.8+
- Pandas, NumPy, SciPy, sklearn for data manipulation and statistical modeling

