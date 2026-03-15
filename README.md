# 📈 AI Stock Price Prediction using LSTM

A deep learning project that predicts stock prices using **Long Short-Term Memory (LSTM) neural networks** trained on historical financial time-series data.

This project demonstrates how artificial intelligence can analyze historical market trends and generate predictions for future stock prices.

---

# 🚀 Project Overview

Financial markets generate sequential time-series data where each value depends on previous values. Traditional machine learning models struggle to capture these long-term dependencies.

To address this challenge, this project uses **LSTM (Long Short-Term Memory)** networks — a specialized neural network architecture designed for sequence prediction.

The model learns patterns from historical stock prices and predicts future values based on those learned trends.

---

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

git clone https://github.com/yourusername/ai-stock-price-prediction-lstm.git

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

# 👨‍💻 Author

Henil Modi
Engineering Student | Interested in Artificial Intelligence & Cybersecurity
