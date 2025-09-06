# 📈 LSTM Stock Price Prediction Model

A **real-time stock forecasting application** powered by **LSTM (Long Short-Term Memory) networks** and **Streamlit**. The model leverages historical stock data to predict future prices and ensures robust performance evaluation using **K-Fold Cross Validation**.

---

## 🔧 Key Features

* 🧠 **LSTM-powered predictions** for accurate time-series forecasting
* 🔁 **K-Fold Cross Validation** for reliable model performance assessment
* 📊 **Interactive visualizations** including:

  * Historical & predicted closing prices
  * Training loss across epochs
  * Mean Absolute Percentage Error (MAPE)
* 📅 Flexible **forecasting window (1–7 days)**
* ⚙️ Adjustable **training settings** (epochs, folds)
* 🔐 **Secure API integration** with Alpha Vantage for real-time stock data

---

## 🛠️ Tech Stack

* **Frontend/UI:** Streamlit
* **Backend/Model:** TensorFlow (Keras, LSTM)
* **Data Source:** Alpha Vantage API
* **Data Processing & Visualization:** Pandas, NumPy, Matplotlib
* **Model Evaluation:** Scikit-learn (`KFold`, `mean_absolute_percentage_error`)
