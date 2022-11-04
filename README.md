# Glen-Quadros-Stock-Market-Prediction-using-Tenserflow

In this model, we use the previous 100 days data to make prediction for the future data. It takes a stock ticker as a user input. The stock data is then downloaded using the yfinance python library. The graphs are plotted using the matplotlib python library. 

For the machine learning part, we split the data into 2 parts: the training part and the testing part. The training part comprises of 70% of the data and the rest is the testing part. The data is scaled using the MinMaxScaler. Using Tensorflow, we import the LSTM (Long Short Term Memory). We then fit the model with the training data. After making predictions, we then convert the scaled data back to the original form. I then plot the original price vs the predicted price using the matplotlib pyhton library.
