# Sales Forecasting with Prophet

## Overview
This project forecasts future sales using Facebook Prophet, a time-series forecasting model. It aggregates historical weekly sales data, trains a forecasting model, evaluates accuracy using MAE and MAPE, and visualizes actual vs. predicted sales in Power BI.

## Dataset
- **Source:** [Walmart Sales Forecasting Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/walmart-dataset)
- Historical weekly sales data across multiple stores and departments.

## Approach
1. **Data Aggregation** — Grouped weekly sales data by date across all stores/departments.
2. **Model Training** — Trained a Prophet time-series model on historical sales data.
3. **Forecasting** — Generated a 90-day sales forecast.
4. **Evaluation** — Measured forecast accuracy using MAE (Mean Absolute Error) and MAPE (Mean Absolute Percentage Error).
5. **Visualization** — Exported forecast results and built an interactive line chart in Power BI comparing actual vs. predicted sales.

## Tech Stack
- Python
- Prophet (Facebook/Meta)
- Pandas, NumPy, Scikit-learn
- Power BI

## Results
| Metric | Score |
|--------|-------|
| MAE | XX |
| MAPE | XX% |

*(Replace with your actual output)*

## Visualization
![Sales Forecast Chart](sales_forecast_chart.png)

## How to Run
1. Clone this repo
2. Install dependencies: `pip install pandas numpy scikit-learn prophet`
3. Download the dataset from Kaggle
4. Run the notebook: `sales_forecasting_prophet.ipynb`

## Key Learnings
- Aggregating multi-dimensional data (store/department level) into a single time series for forecasting
- Evaluating forecast accuracy using MAE and MAPE rather than classification metrics
- Connecting Python-generated forecasts to BI tools for stakeholder-friendly visualization
