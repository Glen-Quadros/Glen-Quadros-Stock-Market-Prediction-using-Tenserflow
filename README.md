# Glen-Quadros-Stock-Market-Prediction-using-Tensorflow

Stock market prediction using TensorFlow is a technique that involves using machine learning algorithms to analyze historical data and predict future trends in the stock market. Using TensorFlow, I build a complex neural networks that analyzes large amounts of data to make accurate predictions. The model is trained using historical data, and then used to make predictions about future trends in the stock market.

In this model, I use the previous 100 days data to make prediction for the future data. The model takes a stock ticker as a user input. The stock data is then downloaded using the yfinance python library. The graphs are plotted using the matplotlib python library. 

For the machine learning part, I split the data into 2 parts: the training part and the testing part. The training part comprises of 70% of the data and the rest is the testing part. The data is noramlized using the MinMaxScaler. Using Tensorflow, I import LSTM (Long Short Term Memory). I then fit the model with the training data. After making predictions, we then convert the scaled data back to the original form. I then plot the original price vs the predicted price using the matplotlib python library.

It is important to note that stock market prediction using machine learning is not always accurate and there are many factors that can impact the stock market, making it difficult to predict with complete accuracy. 
