# Netflix-Subscription-Forcasting
This repository contains a Python-based time series analysis project that utilizes ARIMA (AutoRegressive Integrated Moving Average) modeling to forecast number of subscribers . The project aims to demonstrate how to handle, prepare, and forecast time series data using a well-known statistical method 
# Project Overview
The project follows a systematic approach to time series forecasting:

1.**Data Preprocessing**: The time series data, which includes a 'Time Period' as the index and 'Subscribers' as a column, is first preprocessed to ensure it is in the correct format for analysis.

2.**Training and Testing Split**: The dataset is split into training and testing sets based on a temporal cutoff point, ensuring that the model is validated on unseen data.

3.**Model Building**: An ARIMA model is built using the statsmodels library in Python. The hyperparameters (p,d,q) are determined ACF and PCAF plots.

4.**Model Training**: The ARIMA model is trained on the training set to understand the underlying patterns in the subscriber count over time.

5.**Forecasting**: The model makes predictions for the time period covered by the testing set and also make future predictions.

6.**Evaluation**: The model's predictions are compared against the actual subscriber data in the testing set, and residuals are calculated to evaluate forecasting accuracy.
