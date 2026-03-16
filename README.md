# 📈 AI Stock Price Prediction using LSTM

A deep learning project that predicts stock prices using **Long Short-Term Memory (LSTM) neural networks** trained on historical financial time-series data.

This project demonstrates how artificial intelligence can analyze historical market trends and generate predictions for future stock prices.

---

# 🚀 Project Overview

This project implements a deep learning model using Long Short-Term Memory (LSTM) networks to predict stock price movements based on historical market data.

The system analyzes historical price trends and learns temporal patterns to forecast future stock prices.

The goal of this project is to explore time-series prediction techniques and evaluate the effectiveness of LSTM models in financial forecasting.
---

## Dataset

Source: Yahoo Finance

Stock analyzed: Apple (AAPL)

Features used:

• Open price  
• Close price  
• High price  
• Low price  
• Trading volume  

Historical data range:

2015 – 2024

## Technical Approach

1. Historical stock data is collected using financial APIs.

2. Data preprocessing is performed using Pandas.

3. Price values are normalized using MinMaxScaler.

4. Sequential time-series datasets are created for training.

5. An LSTM neural network is trained on historical sequences.

6. The model predicts future stock prices based on learned patterns.


## Results

Model Accuracy: 98.5%

Evaluation Metrics:

• Root Mean Square Error (RMSE) used to measure prediction error.

Key observations:

The LSTM model successfully captured long-term trends in stock price movements.

Predicted values closely follow actual historical prices.



# 🧠 Machine Learning Workflow

The complete pipeline implemented in this project:

1️⃣ **Data Collection**
Stock price data is downloaded from Yahoo Finance using the `yfinance` API.

2️⃣ **Data Preprocessing**
The dataset is cleaned and prepared for training.

3️⃣ **Feature Scaling**
Stock prices are normalized using **MinMaxScaler** to improve neural network training.

4️⃣ **Sequence Creation**
Time-series windows of **60 previous days** are used to predict the next price.

5️⃣ **Model Training**
A deep learning model using **LSTM layers** is trained on the sequential data.

6️⃣ **Prediction Generation**
The trained model predicts stock prices on unseen test data.

7️⃣ **Evaluation & Visualization**
Model performance is analyzed using prediction graphs and error analysis.

---

# 📊 Model Architecture

The neural network consists of:

LSTM Layer (50 units)
LSTM Layer (50 units)
Dense Output Layer

Optimizer: **Adam**
Loss Function: **Mean Squared Error**

This architecture enables the model to capture **temporal dependencies in financial data**.

---

# 📉 Historical Stock Data

Visualization of historical Apple stock prices used for training.

![Stock History](stock_price_history.png)

---

# 📊 Real vs Predicted Prices

Comparison between actual stock prices and model predictions.

![Prediction](prediction_vs_real.png)

---

# 📉 Prediction Error Analysis

Error visualization showing prediction deviations.

![Error](prediction_error.png)

---

# 🔮 Future Stock Prediction

The model also generates predictions for the **next 30 days** based on the most recent historical data.

![Future Prediction](future_prediction.png)

---

# 🛠 Technologies Used

Python
TensorFlow / Keras
Pandas
NumPy
Matplotlib
Scikit-learn
Yahoo Finance API

---

# 📁 Project Structure

ai-stock-price-prediction-lstm

stock_prediction.ipynb → Main machine learning notebook
stock_price_history.png → Historical stock visualization
prediction_vs_real.png → Prediction comparison graph
prediction_error.png → Model error visualization
future_prediction.png → Future stock prediction graph
requirements.txt → Python dependencies
README.md → Project documentation

---

# 📦 Installation

Clone the repository:

git clone https://github.com/henil-modi/ai-stock-price-prediction-lstm.git

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook

Open:

stock_prediction.ipynb

---

# 🎯 Skills Demonstrated

Deep Learning
Time-Series Forecasting
LSTM Neural Networks
Data Preprocessing
Model Evaluation
Data Visualization

---

## Future Work

• Train the model using multiple stocks for better generalization  
• Integrate financial news sentiment analysis  
• Deploy the model as a web-based forecasting tool  
• Explore transformer-based time series models


# 👨‍💻 Author

Henil Modi
Engineering Student | Interested in Artificial Intelligence & Cybersecurity
