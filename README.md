# Python-LSTM-Model
This project attempts to predict the stock price of Apple using an LSTM model.
We begin by using pandas datareader to source yahoo's data on Apple's stock prices. After that, we scale the data since that is essential for the ML model we will build. 
Next, we use 60 days of data to help predict the data of the 61st day, and so on.
We use sklearn for this.
Lastly, we build a visualization that displays the predicted data along with the actual data to view the ability of the model to predict stock prices. 
While it was obviously not a perfect predictor, it mapped the ups and downs of the stock reasonably well, which is a promising start!
