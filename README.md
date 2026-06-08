### Project Overview

* Fetched and preprocessed historical Ethereum price data from the Binance API and normalized features using **MinMaxScaler** for effective sequence modeling.
* Performed **Exploratory Data Analysis (EDA)** using Matplotlib and Seaborn to identify market trends, volatility patterns, and feature correlations.
* Engineered time-series features including **MA100, MA200, and MA365** to capture long-term trends and reduce market noise.
* Designed and optimized a **multi-layer LSTM network** using TensorFlow/Keras, tuning model architecture and hyperparameters to minimize **Mean Squared Error (MSE)**.
* Evaluated model performance through predicted vs actual price visualizations and trend analysis.
* Implemented **10-day future price forecasting** using an autoregressive approach based on the most recent 100 time steps.
