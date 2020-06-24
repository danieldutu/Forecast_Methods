# Forecast_Methods
## Different forecast approaches side by side comparison on a dataset.

The purpose of this notebook is to find the optimal approach for forecasting a timeseries.


# Model Building
First, I transformed the column variable into variables. I also split the data into train and tests sets with a test size of 20%.

I tried three different models and evaluated them using Mean Absolute Error. I chose MAE because it is relatively easy to interpret and outliers aren’t particularly bad in for this type of model.

# I tried three different models:

**ARIMA** 
**Long Short Term Memory**  
**Prophet** 

LSTM model far outperformed the other approaches on the test and validation sets.

ARIMA: MAE = 
Long Short Term Memory: MAE = 
Prophet: MAE = 
