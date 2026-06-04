# ADV-Task3-Task4-WorldBank-PowerBI
Interactive and predictive Power BI dashboard using World Bank web data for Advanced Data Visualization
# Global Economic & Development Intelligence Dashboard

## Project Overview
This project was developed for the Advanced Data Visualization course. It presents an interactive Power BI dashboard using web-based World Bank data. The cleaned dataset contains multiple World Bank indicators including GDP, GDP per capita, population, inflation, agriculture contribution, unemployment, and exports for selected countries from 2000 to 2024.

## Task 3: Interactive Power BI Dashboard
The dashboard includes:
- Web data import using World Bank API
- Data cleaning and transformation in Power Query
- Fact and dimension data modeling
- DAX calculated columns and measures
- KPI cards
- Line chart for trend analysis
- Bar chart for country ranking
- Donut chart for distribution analysis
- Structured data table
- Region, country, category, indicator, and year slicers
- Cross-filtering and drill-down functionality

## Data Source
World Bank Indicators API  
https://api.worldbank.org

## Selected Indicators
- GDP Current US$
- GDP per capita
- Total population
- Inflation annual %
- Agriculture value added % of GDP
- Unemployment total %
- Exports of goods and services % of GDP

## Tools Used
- Microsoft Power BI
- Power Query
- DAX
- World Bank API

## Task 4 Extension
The same dataset will be used for predictive analytics and machine learning-based forecasting in Task 4.

## Task 4: Machine Learning Forecasting Dashboard

Task 4 extends the interactive Power BI dashboard with machine learning-based forecasting.

### Machine Learning Approach

* Algorithm: Linear Regression
* Input feature: Year
* Target variable: Indicator Value
* Forecast period: 2025–2029
* Separate models trained for each country and indicator combination

### Model Evaluation

The models were evaluated using:

* Mean Absolute Error
* Root Mean Squared Error
* R² Score

### Predictive Dashboard Features

* Actual vs Predicted Trend chart
* Future Forecast Projection chart
* Error Analysis table
* Prediction and forecast-growth KPI cards
* Interactive filters for region, country, category, indicator, year, and forecast type

### Task 4 Files

* `WorldBank_Forecasting_Model.ipynb`
* `WorldBank_Forecast_Results.csv`
* `WorldBank_Model_Metrics.csv`
* Updated Power BI `.pbix` file
* Predictive-dashboard screenshots

