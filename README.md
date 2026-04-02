#  Traffic Volume Prediction

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15gjs1AmSI_zBVIWfYf0ieOwJV5CSlxUQ)

---

## Project Overview

This project aims to predict **traffic volume** using machine learning techniques based on historical traffic and weather data.

It includes:
- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model building  
- Model evaluation  

---

## Dataset

The dataset used is the **Metro Interstate Traffic Volume Dataset**, which contains hourly traffic data from 2012 to 2018.

### Features:
- `date_time` → Timestamp  
- `traffic_volume` → Target variable  
- `temp`, `rain_1h`, `snow_1h`  
- `clouds_all`  
- `weather_main`, `weather_description`  
- `holiday`  

---

## Project Structure

Traffic-Volume-Prediction/
│── traffic_volume_prediction.ipynb # Google Colab Notebook
│── Metro_Interstate_Traffic_Volume.xlsx # Dataset
│── README.md


---

## Technologies Used

- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab  

---

## How to Run (Google Colab)

1. Click the **Open in Colab** button above  
2. Upload dataset
3. Load dataset
4. 4.Run all cells

---

## Models Used

Models Used
Linear Regression
Decision Tree Regressor
Random Forest Regressor

---
## Results
Tree-based models performed better than Linear Regression
Data preprocessing improved accuracy
