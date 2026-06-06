# Sales Forecasting System Using Time-Series Analysis

## 📌 Overview
This project focuses on predicting future sales using time-series analysis and machine learning techniques. It analyzes historical sales data and applies different models to forecast future trends.

## 📊 Dataset
The dataset contains historical sales records with columns such as Date and Sales. The data is aggregated on a daily basis for analysis.

## 🎯 Objective
- Analyze historical sales patterns
- Predict future sales using regression and time-series models
- Compare different forecasting approaches

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## 🔍 Methodology

### 1. Data Preprocessing
- Converted Date column into datetime format
- Aggregated sales on a daily basis

### 2. Linear Regression Model
- Converted time into numerical format (Day)
- Trained Linear Regression model on daily sales
- Predicted sales trend based on time

### 3. Time-Series Forecasting
- Converted data into time-series format
- Applied Exponential Smoothing model
- Captured trend and seasonality (weekly pattern)

### 4. Forecasting
- Predicted sales for the next 90 days
- Compared actual sales with model predictions

## 📈 Results
- Linear Regression captures overall trend
- Exponential Smoothing performs better for time-series patterns
- Forecasting helps in understanding future sales behavior

## 📊 Visualization
Graphs include:
- Actual Sales Trend
- Regression Predictions
- Exponential Smoothing Forecast
- Final comparison of all models

## 🚀 How to Run
1. Open notebook.ipynb in Jupyter Notebook or VS Code
2. Install required libraries:
3. Run all cells sequentially

## 👩‍💻 Author
This project was completed as part of ML internship training and learning experience.