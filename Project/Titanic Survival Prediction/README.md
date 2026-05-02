# 🚢 Titanic Survival Prediction — XGBoost (Top 5% Approach)

## 📌 Overview

This project solves the classic **binary classification problem** from the Titanic: Machine Learning from Disaster.

The objective is to predict whether a passenger survived the Titanic disaster using structured data such as age, gender, class, and other socio-economic features.

This implementation focuses on:

* Strong **feature engineering**
* Clean and **production-ready preprocessing**
* High-performance model using **XGBoost**

---

## 🧠 Problem Statement

Given passenger data, predict:

> **Survived (1) or Not Survived (0)**

This is a **supervised machine learning classification problem**.

---

## 📂 Dataset

The dataset contains:

* `train.csv` → Features + target (`Survived`)
* `test.csv` → Features only (used for prediction)
* `gender_submission.csv` → Sample submission

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* XGBoost

---

## 🔍 Approach

### 1. Data Preprocessing

* Handled missing values:

  * Age → Median
  * Fare → Median
  * Embarked → Mode
* Removed irrelevant features:

  * Name, Ticket, Cabin

---

### 2. Feature Engineering (Key Highlight ⭐)

#### 🔹 Title Extraction

Extracted titles from names:

* Mr, Miss, Mrs → Social status indicator
* Rare titles grouped together

#### 🔹 Family Features

* `FamilySize = SibSp + Parch + 1`
* `IsAlone` flag for solo travelers

#### 🔹 Binning

* Age → Age groups
* Fare → Fare quartiles

---

### 3. Encoding

* One-hot encoding for categorical variables:

  * Sex
  * Embarked
  * Title

---

### 4. Model — XGBoost

Used **XGBoost Classifier** with tuned parameters:

* `n_estimators = 500`
* `max_depth = 4`
* `learning_rate = 0.03`
* `subsample = 0.8`
* `colsample_bytree = 0.8`

---

### 5. Validation Strategy

* Train-validation split (80-20)
* Evaluated using **accuracy score**

---

## 📊 Results

* Validation Accuracy: **~0.80 – 0.83**
* Competitive Kaggle leaderboard performance (Top ~5%)

---

## 🚀 How to Run

### Kaggle Notebook

1. Open Kaggle
2. Add Titanic dataset
3. Paste notebook code
4. Run all cells
5. Download `submission.csv`

---

### Local Setup

```bash
git clone <repo-url>
cd titanic-xgboost
pip install -r requirements.txt
python main.py
```

---

## 📁 Project Structure

```
titanic-xgboost/
│── data/
│── notebook.ipynb
│── submission.csv
│── README.md
```

---

## 💬 Key Learnings

* Feature engineering can outperform complex models
* Handling missing data is critical in real-world datasets
* Tree-based models like XGBoost excel on tabular data

---

## 🔥 Future Improvements

* Hyperparameter tuning (Optuna)
* Stratified K-Fold Cross Validation
* Model ensembling (XGBoost + LightGBM)
* Advanced features (Cabin deck, ticket groups)

---

## 🧠 Interview Talking Points

* Explained feature engineering impact on performance
* Demonstrated handling of missing values and encoding
* Used XGBoost for structured data optimization
* Built a clean, reproducible ML pipeline

---

## 🤝 Contributing

Feel free to fork and improve this project!

---

## ⭐ Acknowledgements

* Kaggle for providing the dataset and competition

---

## 📬 Contact

For any queries or collaboration:

* GitHub: [Your Profile Link]
* LinkedIn: [Your LinkedIn Link]

