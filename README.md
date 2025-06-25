# 🌧️ Rainfall Prediction using Machine Learning

This project aims to predict whether it will rain the next day using historical weather data. With timely and accurate rainfall predictions, such models can support better agricultural planning, disaster preparedness, and general weather forecasting.

---

## 📁 About the Dataset

The dataset is sourced from **Kaggle** and includes daily weather observations. Each row represents weather data for a specific day with the following features:

- `day` – The day of observation  
- `pressure` – Atmospheric pressure
- `maxtemp` – Maximum temperature recorded  
- `temparature` – Average temperature of the day  
- `mintemp` – Minimum temperature recorded  
- `dewpoint` – Dew point temperature  
- `humidity` – Humidity level (%)  
- `cloud` – Cloud cover level  
- `rainfall` – Amount of rainfall (mm)  
- `sunshine` – Hours of sunshine  
- `winddirection` – Direction of the wind  
- `windspeed` – Speed of the wind  

The **target variable** is whether it rained the next day, making this a **binary classification** problem. The dataset contains a mix of numerical and categorical features, which were cleaned and preprocessed before training.

---

## 🧠 Models Applied

Several classification algorithms were implemented and evaluated:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Classifier (SVC)  
- Decision Tree  
- Random Forest  

---

## ✅ Best Model Performance

Out of all the models tested, the **Random Forest classifier** achieved the highest accuracy of **86%**, making it the most effective model for this rainfall prediction task.
