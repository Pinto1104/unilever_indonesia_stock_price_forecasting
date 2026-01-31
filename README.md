# 📈 **Stock Price Forecasting Using LSTM, GRU, and XGBoost (Case Study: PT Unilever Indonesia)**
A time-series forecasting project comparing LSTM, GRU, and XGBoost models to predict PT Unilever Indonesia’s stock closing prices using historical data. This study uses closing price as the sole input feature for stock price forecasting. The closing price represents the final market consensus for a given trading day, integrating all available information such as intraday price movements, trading volume, and market sentiment.

# 📌 **Problem**
Stock prices are highly sensitive to external events and market sentiment.
This project aims to compare deep learning and machine learning models for short-term stock price forecasting.

# 🎯 **Objective**
* Forecast UNVR stock prices (15 days ahead)
* Compare LSTM, GRU, and XGBoost
* Identify the most accurate model based on MAPE

# 📊 **Dataset**
* **Source:** Yahoo Finance
* **Period:** June 2017 – June 2024
* **Feature:** Closing price
* **Total observations:** 1,735 days

# ⚙️ Methodology
* **Min-Max normalization** -> Preprocessing
* **Data split** ->  For LSTM and GRU ratio of 80% for 
training data, 10% for testing data, and 10% for validation data 
is used to divide the data. And for X
## Models
* Long Short Term Memory (LSTM)
* Gated Recurrent Unit (GRU)
* Extreme Gradient Boosting (XGBoost)
## Evaluation metrics
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)

# 💯 Result
| Model | MAPE |
|---|---|
| LSTM | 9.25% |
| GRU | 2.21% |
| XGBoost | 26.45% |
GRU achieved the highest accuracy for short-term forecasting. with results indicating a short-term downward price trend.

# 💡 Insight
GRU outperformed LSTM and XGBoost in capturing short-term stock price dynamics, making it more suitable for time-series forecasting with limited features

# Related Article
This project was previously discussed in a technical article on Medium, focusing on the modeling approach and interpretation of results.  
👉 [Medium Article Link](https://medium.com/@dipintom3/boycotting-unilever-what-happens-to-their-stock-prices-5654763c0a9f)

# Contact
Name: Muhammad Kamil Dipinto
Email: dipintom3@gmail.com
LinkedIn: [Muhammad Kamil Dipinto](www.linkedin.com/in/muhammadkamildipinto)
[Portfolio](https://muhammadkamildipintoportfolio.my.canva.site/)

