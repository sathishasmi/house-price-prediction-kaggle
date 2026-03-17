# 🏠 House Price Prediction – Machine Learning Project

## 📌 Project Overview

This project focuses on predicting house prices using machine learning techniques based on the Kaggle dataset **House Prices – Advanced Regression Techniques**.

The project follows a complete ML pipeline including:

* Data analysis
* Feature engineering
* Model training

---

## 📊 Dataset

* Source: Kaggle House Prices Dataset
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
* Files:

  * `train.csv`
  * `test.csv`

The dataset contains multiple features such as:

* Living Area (GrLivArea)
* Basement Area (TotalBsmtSF)
* Floor Area (1stFlrSF, 2ndFlrSF)
* Overall Quality
* Year Built

---

## 🔍 Exploratory Data Analysis (EDA)

Performed:

* Dataset structure analysis (`info()`, `describe()`)
* Missing value check
* Correlation analysis with target variable (`SalePrice`)
* Visualization:

  * Scatter plots (GrLivArea vs SalePrice)
  * Heatmap for feature correlation
  * Distribution plot of SalePrice

---

## 🧠 Feature Engineering

Created new feature:

```python
TotalSF = TotalBsmtSF + 1stFlrSF + 2ndFlrSF
```

This improves model performance by combining important area features.

---

## ⚙️ Data Preprocessing

* Handled missing values
* Selected important numerical features
* Removed irrelevant or weak features

---

## 🤖 Model Used

### Random Forest Regressor

* Used for predicting house prices
* Handles non-linear relationships effectively
* Works well with tabular data

---

## 🏋️ Model Training

* Split data into training and validation sets
* Trained using `RandomForestRegressor`
* Evaluated model performance

---

## 📈 Evaluation

* Compared predicted vs actual values
* Used correlation and visual analysis to understand model performance

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the notebook:

```bash
jupyter notebook house_price.ipynb

---

## 💡 Key Learnings

* Understanding dataset using EDA
* Feature engineering improves model performance
* Correlation helps in feature selection
* Random Forest works well for regression problems

---

## 🔮 Future Improvements

* Add XGBoost and LightGBM models
* Use ensemble methods
* Hyperparameter tuning
* Improve Kaggle leaderboard score

---

## Acknowledgements

* Kaggle dataset
* Open-source ML libraries

---
