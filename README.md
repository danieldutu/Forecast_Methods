# Forecast-Models-Showdown
## Different forecast approaches side by side comparison on a dataset.

The purpose of this notebook is to find the optimal approach for forecasting a timeseries.


# Model Building
First, I transformed the column variable into variables. I also split the data into train and tests sets with a test size of 20%.

I tried three different models and evaluated them using RMSE and MSE. I chose them because it is relatively easy to interpret and outliers aren’t particularly bad in for this type of model.

# Model Performance

I tried three different models: <br>
**ARIMA** <br>
**Long Short Term Memory**  <br>
**Prophet** <br>

ARIMA model far outperformed the other approaches on the test sets, but the models weren't tuned at their maximum performance.


| Model | RMSE | MSE |
| --- | --- | --- |
| ARIMA | 0.765449 | 0.585912 |
| LSTM | 1.328145| 1.763970 |
| Prophet | 1.591280 | 2.532170|
