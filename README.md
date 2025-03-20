# 📊 Time Series Analysis & Heart Disease Prediction

This repository contains two data science projects focused on **Sales Forecasting** and **Heart Disease Prediction** using machine learning techniques.

---

## 🚀 Project 1: Sales Forecasting using Time Series Analysis

### 📌 Objective  
Analyze historical sales data to identify trends and forecast future sales using the **ARIMA model**.

### 🔍 Steps Involved  
1. **Data Preprocessing**:  
   - Loaded and cleaned the sales dataset.  
   - Converted the date column to datetime format.  

2. **Data Visualization**:  
   - Plotted sales trends using line charts.  
   - Used moving averages to identify patterns.  

3. **Time Series Forecasting**:  
   - Applied **ARIMA** (AutoRegressive Integrated Moving Average) model.  
   - Tuned parameters using **AIC/BIC values**.  

4. **Model Evaluation**:  
   - Measured accuracy using **Root Mean Squared Error (RMSE)**.  
   - Compared actual vs predicted sales values.  

### 📊 Technologies Used  
- **Python**, **Pandas**, **Matplotlib**, **Seaborn**, **Statsmodels**  

### 📁 Dataset  
- `sales_data.csv`: Contains historical sales data with `Date` and `Sales` columns.  

---

## ❤️ Project 2: Heart Disease Prediction using Logistic Regression

### 📌 Objective  
Predict whether a patient has **heart disease** based on key medical parameters.  

### 🔍 Steps Involved  
1. **Data Preprocessing**:  
   - Checked for missing values and handled duplicates.  
   - Normalized numerical features (Age, Cholesterol, Blood Pressure).  

2. **Feature Engineering**:  
   - Encoded categorical variables like `Gender`.  
   - Split data into training & testing sets.  

3. **Model Training & Evaluation**:  
   - Trained a **Logistic Regression** model.  
   - Evaluated performance using **Confusion Matrix, Precision, Recall, and F1-score**.  

### 📊 Technologies Used  
- **Python**, **Pandas**, **Scikit-Learn**, **Matplotlib**, **Seaborn**  

### 📁 Dataset  
- `heart_disease.csv`: Contains patient health data with columns like `Age`, `Gender`, `Cholesterol`, `Blood Pressure`, and `Heart Disease` (0/1).  

---
