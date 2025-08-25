# Tata Motors Stock Price Prediction using LSTM

##  Project Overview
This project focuses on **predicting Tata Motors stock prices** using **Long Short-Term Memory (LSTM)**, a type of recurrent neural network well-suited for time-series forecasting.  
We collected the past **5 years of stock price data** and trained an AI model to learn the trends and generate predictions.

##  Dataset
- Source: [Yahoo Finance](https://finance.yahoo.com/) (via `yfinance` Python library)  
- Data: Tata Motors (Ticker: `TATAMOTORS.NS`)  
- Time period: Last **5 years**  
- Features used: `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`

##  Technologies Used
- **Python 3.8+**
- **Libraries:**
  - `pandas`, `numpy` → Data preprocessing
  - `matplotlib`, `seaborn` → Data visualization
  - `scikit-learn` → Scaling & evaluation
  - `tensorflow/keras` → Building LSTM model
  - `yfinance` → Stock data extraction

##  Model Architecture
- LSTM layers with dropout to prevent overfitting  
- Dense layer for final prediction  
- Loss Function: **Mean Squared Error (MSE)**  
- Optimizer: **Adam**  

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TataMotors-Stock-Prediction.git
   cd TataMotors-Stock-Prediction


pip install -r requirements.txt

jupyter notebook TataMotors_Stock_Prediction.ipynb

# TataMotors_Stock_Prediction.ipynb
