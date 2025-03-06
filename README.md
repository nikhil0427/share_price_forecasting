# Time Series Forecasting of Amazon Stock Prices Using Prophet 
This project leverages the Prophet library along with essential Python tools (Pandas, NumPy, Matplotlib, and scikit-learn) to forecast Amazon stock prices. It demonstrates a complete workflow from data preprocessing to model evaluation and visualization.

In this project, historical Amazon stock data is sourced from Yahoo Finance and prepared for time series forecasting. The workflow includes:

- Data Preparation:
    Reading the dataset using Pandas, and restructuring the data by creating a time series-friendly format with ds (date) and y (adjusted closing price) columns.

- Data Splitting:
    Dividing the data into training and testing sets to ensure robust model evaluation.

- Model Training and Prediction:
    Utilizing the Prophet library to train on historical data and predict future stock prices. The model is then used to generate forecasts for the testing period.

- Visualization:
    Employing Matplotlib with the fivethirtyeight style to create clear and professional visualizations of both the forecasted values and the underlying components (trend, seasonality) of the model.

- Performance Evaluation:
    Assessing the accuracy of the forecast using Mean Squared Error (MSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE).
