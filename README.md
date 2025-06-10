# Flight_Fare_Prediction
# ✈️ Flight Fare Prediction - A Classic Time Series Project

Flight fare prediction is a classic time series forecasting problem where historical patterns are analyzed to forecast future flight prices. In today's era of dynamic pricing, predicting airfare helps users make informed decisions on the best time to book a flight.

## 📌 Project Description

In this project, we have developed a Python-based **Flight Fare Prediction App**. The app uses machine learning to predict the fare of a flight ticket based on:

- Departure and arrival dates
- Source and destination cities
- Airline carrier
- Number of stoppages
- Duration of the flight

### 🔍 Why Flight Fare Prediction?

Most modern travel platforms like **Google Flights**, **Skyscanner**, and **MakeMyTrip** provide:
- Current fare status (High/Low/Fair)
- Fare history trends
- Suggestions on when to book tickets

Our project aims to replicate similar functionalities using machine learning techniques.

---

## 🚀 Features

- Predicts fare based on multiple travel parameters
- Implements data preprocessing and feature engineering
- Trained with scikit-learn models for regression
- Flask-based REST API to serve predictions
- Clean UI (optional extension) using HTML/JS or any frontend framework

---

## 🛠️ Tech Stack

- **Python** 🐍
- **Flask** - Web Framework
- **scikit-learn** - ML Model Training
- **pandas**, **numpy** - Data Handling
- **joblib** - Model Serialization

---

## 📦 Dependencies

The following packages are used in the project:

```txt
click==8.1.3
Flask==2.2.2
Flask-Cors==3.0.10
importlib-metadata==4.12.0
itsdangerous==2.1.2
Jinja2==3.1.2
joblib==1.1.0
MarkupSafe==2.1.1
numpy==1.23.2
pandas==1.4.3
python-dateutil==2.8.2
pytz==2022.2.1
scikit-learn==1.1.2
scipy==1.9.0
six==1.16.0
sklearn==0.0
threadpoolctl==3.1.0
Werkzeug==2.2.2
zipp==3.8.1
