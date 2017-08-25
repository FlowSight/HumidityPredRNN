# HumidityPredRNN
​UCI air quality data obtained from https://archive.ics.uci.edu/ml/datasets/Air+Quality .It contains one year data of parameters like NOx,CO,PT08,NMHC,Temp etc with time interval of one hour. The object is to predict absolute humidity (AH) based on LSTM  using multivariate time-series concept( [t-1] -> [t] ).

All codes are in humidityPredRNN notebook.

As discrete data to be predicted we check only RMSE which shows up to be around 12 with 70 epochs and rmsprop optimizer.
