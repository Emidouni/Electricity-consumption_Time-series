Introduction

This project involves a comprehensive time series analysis of power consumption data, covering multiple forecasting models and methodologies. The dataset consists of timestamps, power consumption (kW), and temperature (C°) data, with an interval of 15 minutes between observations over a period of 52 days. The analysis includes data preprocessing, handling missing values, splitting the data into training, testing, and unseen datasets, and applying various forecasting models.

Key Steps in the Analysis:
1. Data Preprocessing: Addressing missing timestamps and anomalies in the dataset.
2. Exploratory Data Analysis: Plotting power consumption and temperature over time to identify patterns and anomalies.
3. Data Splitting: Dividing the data into training, testing, and unseen sets for model validation and forecasting.
4. Data Imputation: Implementing a moving average imputation to handle missing values effectively.
5. Time Series Decomposition: Analyzing the trend, seasonality, and residuals of the power consumption data.
6. Modeling and Forecasting: Applying models such as Additive and Multiplicative Holt-Winters and Auto ARIMA, both with and without temperature as an explanatory variable.
7. Model Evaluation: Assessing model performance using cross-validation and calculating the RMSE to compare accuracy.
8.Forecasting: Using the best-performing model (Auto ARIMA with temperature) to forecast unseen power consumption values.

Detailed Report
All the methodologies, tests, and detailed analyses are documented in the Report.pdf. This report includes:

* A detailed explanation of the data preprocessing steps.
* Exploratory data analysis with visualizations.
* A thorough explanation of the forecasting models used and their respective performances.
* The process of applying Auto ARIMA with temperature for improved accuracy.
* Conclusions drawn from the analysis and future forecasting using the selected model.
Please refer to Report.pdf for a comprehensive understanding of the methodologies and tests conducted throughout this project.

