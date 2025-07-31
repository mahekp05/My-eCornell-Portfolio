# 🏡 Airbnb Instant Booking Prediction

This project predicts whether an Airbnb listing is **instantly bookable** using supervised machine learning. Built as part of a lab assignment, the project applies industry-grade practices such as **data cleaning**, **feature engineering**, **class imbalance handling**, and **hyperparameter tuning** to produce interpretable and high-performing models.

---

## 📄 Project Summary

Given a dataset of Airbnb listings (New York City), the objective is to classify listings as instantly bookable or not. This has practical value for hosts and platforms aiming to improve user experience and reduce booking friction.

---

## 📊 Key Steps

- 🔍 **Exploratory Data Analysis (EDA)**  
  Visualized price distribution, missing values, and correlations

- 🧹 **Data Preprocessing**  
  - Removed irrelevant columns  
  - Handled missing values (e.g., review scores)  
  - One-hot encoded categorical features  
  - Addressed class imbalance via resampling and model tuning

- 🧠 **Modeling**  
  - Trained baseline models (Logistic Regression, Random Forest)  
  - Tuned hyperparameters using `GridSearchCV`  
  - Compared performance using precision, recall, F1, and ROC AUC

---

## 🧪 Final Model Performance

- ✅ Logistic Regression: Good interpretability, decent F1
- ✅ Random Forest: Better accuracy & recall, strong ROC AUC
- 📌 Final model used **Random Forest with tuned depth & estimators**

---

## 📦 Tools & Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
