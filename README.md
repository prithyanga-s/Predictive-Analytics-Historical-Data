# 📊 Predictive Analytics Using Historical Data

## 📌 Project Overview

This project demonstrates **Predictive Analytics Using Historical Data** by analyzing historical monthly sales data and building machine learning models to forecast future sales.

The project covers data preprocessing, exploratory data analysis, trend visualization, predictive modeling, model evaluation, and future sales forecasting.

---

## 🎯 Objectives

- Analyze historical sales data
- Clean and preprocess the dataset
- Identify sales trends over time
- Build predictive regression models
- Evaluate model performance using different metrics
- Forecast future sales
- Visualize historical and predicted sales

---

## 🗂️ Dataset

The project uses monthly sales data covering:

**January 2023 – December 2024**

The dataset contains:

| Column | Description |
|---|---|
| Month | Month and year of the sales record |
| Sales | Monthly sales value |

A time-based feature was created to support regression modeling.

---

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 🤖 Machine Learning Models

Three regression models were implemented and compared:

### 1. Linear Regression

Used to identify the overall linear trend in historical sales data and forecast future sales.

### 2. Polynomial Regression

A degree-2 polynomial regression model was used to capture the nonlinear trend in the sales data.

### 3. Random Forest Regression

A Random Forest regression model was implemented for comparison with the regression-based approaches.

---

## 📈 Model Evaluation

The models were evaluated using:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

### Model Comparison

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1613.09 | 1830.81 | 0.2363 |
| Polynomial Regression | 620.99 | 739.88 | 0.8753 |
| Random Forest Regression | 4172.67 | 4669.05 | -3.9671 |

The results show how different regression approaches behave
