# CSE573-Anomaly_Detection

Problem: 
Identification of items, events or observations which do not conform to an expected pattern or other items in a (time-series) dataset.
For this project, the objective is to detect anomalies within a currency exchange data that varies with respect to time.

Data Sets:
The currency exchange rate data of the European (€) and United States ($) currencies will be used for detecting the anomalies. This data comprises the currency exchange rates spanning from 2021-01-28 to 2004-07-29 across all the working days. This data set consists of data items of 24 hours, measured each minute. There are 6 million rows in the data and 5 columns which are Time, Open, High, Low, Close and Volume. For this project, the Date, Time and Close columns will be used to detect anomalies with the respect to the closing price. The objective is to use a subset of the 6 million rows to train the model.

Algorithms Implemented:
LSTM with Autoencoder
Arima Model
GRU with Autoencoder
Variational Recurrent Autoencoder
