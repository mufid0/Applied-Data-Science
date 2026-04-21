# 📉 Customer Churn Prediction & Retention Analysis

## 📌 Overview

This project builds an end-to-end machine learning pipeline to analyze and predict customer churn.
It focuses on identifying key behavioral and financial factors that influence customer attrition and provides insights to support retention strategies.

---

## 🎯 Objectives

* Understand customer behavior and churn patterns
* Engineer meaningful features for predictive modeling
* Train and evaluate machine learning models
* Identify key drivers behind customer churn

---

## 📂 Project Structure

```text id="cc_struct"
Customer-Churn/
│
├── churn_analysis.ipynb
├── churn_modeling.ipynb
└── README.md
```

---

## 📊 Dataset

The dataset used in this project is publicly available:

👉 https://www.kaggle.com/datasets/blastchar/telco-customer-churn

It contains customer-level information including:

* Demographics
* Account details (tenure, contract type)
* Services subscribed
* Billing information
* Target variable: **Churn (Yes/No)**

---

## 📓 Notebooks

| Notebook           | Description                                                       |
| ------------------ | ----------------------------------------------------------------- |
| **Churn Analysis** | Data cleaning, exploratory data analysis, and feature engineering |
| **Churn Modeling** | Model training, evaluation, and optimization                      |

---

## 🔍 Exploratory Data Analysis

* Analyzed churn distribution across customer segments
* Identified patterns in tenure, contract type, and services
* Evaluated data quality and missing values
* Visualized feature relationships

---

## ⚙️ Feature Engineering

* Created tenure-based customer segments
* Derived spending behavior metrics
* Identified high-value and long-term customers
* Transformed categorical variables for modeling

---

## 🤖 Machine Learning

Models implemented:

* Logistic Regression
* Random Forest

Workflow:

* Data preprocessing and encoding
* Train-test split with stratification
* Model training and prediction

---

## 📈 Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

Additional techniques:

* Confusion Matrix
* ROC Curve
* Cross-validation

---

## ⚙️ Optimization

* Hyperparameter tuning using GridSearchCV
* Improved model performance and generalization

---

## 📊 Key Insights

* Customers with shorter tenure are more likely to churn
* Month-to-month contracts show higher churn rates
* Higher monthly charges increase churn probability
* Long-term customers are less likely to churn

---

## 🚀 Outcome

* Built a reliable churn prediction model
* Identified key factors influencing churn
* Developed a structured and reproducible ML pipeline

---

## 🧠 Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory data analysis
* Feature engineering
* Machine learning modeling
* Model evaluation and optimization

---

## 🔮 Future Improvements

* Advanced models (XGBoost, Gradient Boosting)
* Model deployment (Streamlit)
* Real-time prediction system

---

## 👨‍💻 Author

**Mufid Panhalkar**
Aspiring Data Scientist | Computer Engineering Student

---
