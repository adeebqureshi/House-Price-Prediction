# House Price Prediction using Machine Learning

## Overview
This project is an end-to-end Machine Learning regression solution developed to predict house prices using various housing features such as area, number of bedrooms, bathrooms, location, construction year, and other property-related attributes. The project demonstrates professional ML engineering practices including data preprocessing, feature engineering, model comparison, evaluation, and model deployment preparation.

---

## Objectives
- Perform Exploratory Data Analysis (EDA)
- Handle missing values effectively
- Apply feature engineering and transformations
- Train and compare multiple regression models
- Evaluate models using RMSE, MAE, and R² Score
- Save the best-performing model for future predictions

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

---

## Machine Learning Models
The following regression algorithms were implemented and compared:

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor

---

## Data Preprocessing
The preprocessing pipeline includes:
- Missing value handling
- One-hot encoding for categorical variables
- Feature scaling using StandardScaler
- Log transformation of target variable
- Feature engineering from date and house attributes

---

## Evaluation Metrics
Models were evaluated using:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score
- Residual Analysis

---

## Project Structure

```bash
House-Price-Prediction/
│
├── data.csv
├── house_price_prediction.ipynb
├── house_price_model.pkl
├── requirements.txt
└── README.md
