**Currency Exchange Anomaly Detection**

This repository provides solutions for anomaly detection in currency exchange rate data using advanced time-series modeling techniques. The primary goal is identifying anomalous observations within historical currency exchange rates between the Euro (€) and US Dollar ($).

Problem Overview

Anomaly detection involves identifying items, events, or observations that deviate significantly from expected patterns in a dataset. This project specifically addresses the detection of anomalies within currency exchange data that varies over time.

**Dataset**

The dataset used in this project comprises currency exchange rates between the Euro (€) and United States Dollar ($) recorded from 2004-07-29 to 2021-01-28. The dataset includes the following characteristics:

Frequency: Recorded each minute for 24 hours per day.

Total Data Size: Approximately 6 million rows.

**Columns Included:**

Time: Time stamp of each record

Open: Opening exchange rate

High: Highest exchange rate in the time interval

Low: Lowest exchange rate in the time interval

Close: Closing exchange rate

Volume: Trading volume

**Used for Detection:**

Date

Time

Close

The detection model is trained using a subset of the entire dataset, emphasizing patterns in the closing prices.

**Algorithms Implemented**

This repository includes implementations of several advanced anomaly detection models:

Long Short-Term Memory (LSTM) Autoencoder

ARIMA (AutoRegressive Integrated Moving Average)

Gated Recurrent Unit (GRU) Autoencoder

Variational Recurrent Autoencoder (VRAE)

Each model leverages the temporal dependencies in the currency exchange rate data to identify anomalies effectively.

**Repository Structure**

.
├── data/
│   └── exchange_rate_data.csv
├── notebooks/
│   ├── LSTM_Autoencoder.ipynb
│   ├── ARIMA_Model.ipynb
│   ├── GRU_Autoencoder.ipynb
│   └── Variational_Recurrent_Autoencoder.ipynb
├── models/
│   └── (saved models)
├── results/
│   └── (output visualizations & results)
├── requirements.txt
└── README.md


**Installation**

Clone the repository:

git clone https://github.com/yourusername/currency-anomaly-detection.git
cd currency-anomaly-detection

Install the required libraries:

pip install -r requirements.txt

**Usage
**
Navigate to the notebooks directory and explore each Jupyter Notebook for detailed instructions and step-by-step implementation guides.

cd notebooks
jupyter notebook
