# 📉 Customer Churn Prediction & Retention Analysis

## 📌 Overview

This project presents a comprehensive end-to-end data science solution for analyzing and predicting customer churn. It combines exploratory data analysis, feature engineering, and machine learning to identify key drivers of churn and build predictive models that support data-driven retention strategies.

The objective is not only to predict churn but also to generate actionable insights that can help businesses reduce customer attrition and improve long-term value.

---

## 🎯 Objectives

* Analyze customer behavior and identify churn patterns
* Engineer meaningful features to enhance predictive power
* Build and evaluate machine learning models
* Provide insights to support retention strategies

---

## 🧠 Project Structure

```text
Customer-Churn/
│
├── churn_analysis.ipynb      # Data exploration and feature engineering
├── churn_modeling.ipynb     # Model training, evaluation, and optimization
├── processed_churn.csv      # Cleaned and engineered dataset
├── README.md
```

---

## 📊 Dataset Description

The dataset contains customer-level information including:

* Demographics (gender, senior citizen status)
* Account details (tenure, contract type, payment method)
* Service usage (internet service, add-ons)
* Financial metrics (monthly and total charges)
* Target variable: **Churn (Yes/No)**

---

## 🔍 Exploratory Data Analysis

* Analyzed distribution of churn across different customer segments
* Identified patterns in tenure, contract type, and service usage
* Evaluated class imbalance and data quality
* Visualized relationships between key variables and churn

---

## ⚙️ Feature Engineering

Key features created to improve model performance:

* **Tenure Groups**: Segmented customer lifespan
* **Average Monthly Spend**: Spending behavior indicator
* **Customer Loyalty Flag**: Long-term vs short-term users
* **High Value Customer**: Based on charge distribution

These features help capture behavioral and financial characteristics beyond raw data.

---

## 🤖 Machine Learning Models

Implemented and compared multiple models:

* Logistic Regression
* Random Forest

Key steps:

* Train-test split with stratification
* Feature encoding and scaling
* Model training and prediction

---

## 📈 Model Evaluation

Models were evaluated using multiple performance metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

Additional evaluation:

* Confusion Matrix
* ROC Curve
* Cross-validation

---

## ⚙️ Model Optimization

* Hyperparameter tuning using GridSearchCV
* Improved generalization and performance
* Selected best-performing model based on F1 score and ROC-AUC

---

## 📊 Key Insights

* Customers with shorter tenure have higher churn probability
* Month-to-month contracts are strongly associated with churn
* Higher monthly charges increase churn likelihood
* Long-term and high-value customers show lower churn rates

---

## 🚀 Outcome

* Developed a predictive model capable of identifying high-risk customers
* Generated actionable insights for retention strategies
* Built a structured and reproducible data science workflow

---

## 🧠 Skills Demonstrated

* Data preprocessing and cleaning
* Exploratory data analysis
* Feature engineering
* Machine learning modeling
* Model evaluation and optimization
* Business-oriented data interpretation

---

## 🔮 Future Improvements

* Incorporate advanced models (Gradient Boosting, XGBoost)
* Perform feature selection and dimensionality reduction
* Deploy model for real-time predictions
* Integrate dashboard for business users

---

## 👨‍💻 Author

**Mufid Panhalkar**
Aspiring Data Scientist | Computer Engineering Student

---

