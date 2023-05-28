# Time Series Analysis using Drug Sales Forecasting

This repository contains a dataset and code for performing drug sales forecasting using time series analysis. The dataset is obtained from the <a href="https://drive.google.com/file/d/1NrJQbY38lNNv4iEihCK9vuww0vPoXPus/view?usp=sharing">provided link</a> and represents monthly drug sale reports.

## Dataset Description
The dataset contains monthly drug sale data. Each row represents a specific month's drug sale report.

## Setup and EDA
To perform exploratory data analysis (EDA) and set up the dataset, follow these steps:
1. Download the dataset from the provided link.
2. Load the dataset into your preferred programming environment or tool.
3. Preview the data to get an overview of its structure and contents.
4. Check for missing data, duplicates, or any other data quality issues.
5. Perform EDA tasks such as scatter plots, histograms, and descriptive statistics to gain insights into the data distribution and characteristics.
6. Perform ETS (Error, Trend, Seasonality) decomposition on the data to capture residuals, seasonality, trend, and observed components.
7. Apply additive and multiplicative decomposition techniques to analyze different aspects of the data.

## ARIMA Modeling
The next step involves creating an ARIMA (AutoRegressive Integrated Moving Average) model to forecast the drug sales data. This is done by following these steps:
1. Create an ARIMA model to forecast the data using the training dataset.
2. Print the Augmented Dickey-Fuller (ADF) statistic and p-value to check for stationarity.
3. Plot the autocorrelation function (ACF) and partial autocorrelation function (PACF) to determine the order of differencing and AR/MA terms for the ARIMA model.
4. Plot the PACF of the 1st differenced series to observe any significant spikes or patterns.
5. Split the data into training and testing sets to evaluate the performance of the ARIMA model.
6. Fit the ARIMA model to the training data.
7. Visualize the forecasted values against the actual data to assess the accuracy of the model's predictions.

Please refer to the code files in this repository for detailed implementation and further instructions on running the analysis.

Note: This dataset and code are provided for educational purposes and serve as a starting point for beginners interested in time series analysis and drug sales forecasting.
