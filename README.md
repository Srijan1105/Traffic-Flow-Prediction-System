# 🚦 Traffic Flow Prediction using Machine Learning

Predict traffic volume for urban roads based on time, weather, and traffic data using a supervised machine learning approach.

## 📌 Project Overview

This project leverages historical traffic and weather data to predict traffic volume. It is built using the **Metro Interstate Traffic Volume** dataset. The aim is to build a machine learning model that helps anticipate congestion trends and supports smarter city planning and traffic management.

---

## 🔍 Problem Statement

Predict the **traffic volume** for a given time, location, and weather condition. This can help in:

- Forecasting traffic for peak and off-peak hours
- Optimizing routes and travel times
- Assisting urban planning with data-driven insights

---

## 📁 Dataset

**Source**: [UCI / Kaggle Metro Interstate Traffic Volume Dataset](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume)

**Features Include:**
- Date and time
- Weather conditions (temperature, rain, snow, clouds)
- Road traffic volume
- Holiday/weekend indicators

---

## 🧰 Technologies Used

| Task                     | Tools/Tech                   |
|--------------------------|------------------------------|
| Language & Libraries     | Python, pandas, numpy        |
| Visualization            | matplotlib, seaborn          |
| Machine Learning         | scikit-learn (Random Forest) |
| Model Saving             | joblib                       |
| Future Dashboard (opt.)  | Streamlit or Dash            |

---

## ⚙️ How it Works

### 1. Data Preprocessing
- Extracted features like hour, day of week, month, and rush hour flags
- Converted weather descriptions to numerical categories

### 2. Model Building
- Used **Random Forest Regressor** to predict traffic volume
- Trained and evaluated the model using RMSE and MAE metrics

### 3. Visualization
- Plotted traffic trends and actual vs predicted values

---

## 📈 Results

| Metric              | Score         |
|---------------------|---------------|
| RMSE (Test Data)    |  445.71       |
| MAE (Test Data)     |  246.71       |

The model successfully captures general traffic patterns, particularly around rush hours and weather changes.

---

## 🚀 How to Run the Project

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/traffic-flow-predictor.git
   cd traffic-flow-predictor
