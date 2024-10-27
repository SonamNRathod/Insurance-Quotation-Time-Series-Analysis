
# Insurance Quotation Forecasting Project

This project aims to forecast monthly insurance quotations for the next 12 months using time series analysis techniques. We analyze historical data from January 2002 to April 2005, and predict future values with confidence intervals.


## Project Overview
In this project, we analyze and forecast the demand for insurance quotations over time. We use historical data to identify trends, seasonal patterns, and randomness, helping to provide insights into the company's quotation demand and aiding in future planning.

## Data
The dataset contains monthly records of insurance quotations from January 2002 to April 2005. This data allows us to:
- Visualize past trends and fluctuations in demand.
- Build a forecast model to predict future quotation demands.

## Forecast Results
The 12-month forecast generated by the Holt-Winters model offers:
- **Point Forecasts**: A specific predicted value for each month.
- **Confidence Intervals**: Ranges (80% and 95%) around each forecast to reflect the uncertainty in predictions.

### Key Insights:
- **Stable Demand**: The forecast shows a stable demand with minor fluctuations.
- **Uncertainty Over Time**: The confidence intervals grow wider further into the future, showing increasing uncertainty.

### Prerequisites
You will need the following R packages:
- `forecast`: For time series forecasting and decomposition.

Install them by running:
```r
install.packages(c("forecast"))
```
