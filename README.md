📈 Stock Price Prediction Using LSTM (2004–2024)
📌 Project Overview

This project focuses on predicting stock prices using Long Short-Term Memory (LSTM), a deep learning model well-suited for time series analysis.
The model is trained on 20 years of historical stock price data (2004–2024) to learn long-term dependencies and trends.

A user-friendly GUI is built using Streamlit, allowing users to interact with the model and visualize actual vs predicted stock prices.

🎯 Objectives

Analyze long-term historical stock price data

Build an LSTM-based time series forecasting model

Predict future stock prices based on past trends

Create an interactive Streamlit web application for easy visualization

🧠 Why LSTM?

Traditional machine learning models struggle with sequential data.
LSTM (Long Short-Term Memory) networks:

Capture long-term dependencies

Handle time-based patterns

Are ideal for financial time series forecasting

🗂 Dataset

Source: Historical stock market data

Time Period: 2004 – 2024

Features Used:

Date

Open

High

Low

Close

Volume

(Closing price is primarily used for prediction)

🛠️ Tech Stack & Tools

Programming Language: Python

Libraries & Frameworks:

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

TensorFlow / Keras

Streamlit

Model: LSTM (Deep Learning – RNN)

⚙️ Project Workflow

Data Collection & Understanding

Data Cleaning & Preprocessing

Handling missing values

Scaling using MinMaxScaler

Creating time-based sequences

Train-Test Split

Time-based split to avoid data leakage

Model Building

LSTM layers with Dense output layer

Model Training

Model Evaluation

Metrics: RMSE, MAE

Visualization

Actual vs Predicted stock prices

GUI Development

Interactive dashboard using Streamlit

📊 Model Evaluation

The model performance is evaluated using:

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

Visual comparison of actual vs predicted prices helps assess trend accuracy.

🖥️ Streamlit GUI Features

Upload or select stock data

Visualize historical stock prices

Display predicted stock prices

Interactive charts and clean UI

Easy-to-use web-based interface

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/stock-price-prediction-lstm.git
cd stock-price-prediction-lstm

2️⃣ Install Required Libraries
pip install -r requirements.txt

3️⃣ Run the Streamlit App
streamlit run app.py

📌 Project Structure
📁 stock-price-prediction-lstm
│── app.py                  # Streamlit GUI
│── model.ipynb             # LSTM model development
│── data.csv                # Stock price dataset
│── requirements.txt        # Dependencies
│── README.md               # Project documentation

🚀 Future Enhancements

Add multi-stock selection

Integrate real-time stock data using APIs

Improve accuracy using Bidirectional LSTM

Add technical indicators (RSI, MACD, Moving Averages)

Deploy the app on cloud platforms (Streamlit Cloud / AWS)

👤 Author

Murali Suvvani
Aspiring Data Analyst / Machine Learning Engineer
Skilled in Python, Time Series Analysis, Deep Learning, and Data Visualization

⭐ Acknowledgements

Open-source Python community

TensorFlow & Streamlit documentation

Financial data providers
