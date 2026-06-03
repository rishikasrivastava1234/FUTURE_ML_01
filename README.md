# Sales & Demand Forecasting for Businesses

## About the Project

As part of my Machine Learning Internship task, I worked on building a sales forecasting model using historical retail sales data.

The objective of this project was to analyze past sales trends and predict future weekly sales using machine learning techniques. Accurate sales forecasting helps businesses manage inventory, improve planning, and make better operational decisions.

---

## Dataset Information

The dataset contains weekly sales records from multiple stores and departments.

Main Features:
- Store ID
- Department ID
- Date
- Holiday Indicator
- Weekly Sales

Dataset Source:
Walmart Sales Forecasting Dataset (Kaggle)

---

## Project Workflow

### 1. Data Understanding
- Loaded and inspected the dataset
- Checked data types and dataset structure
- Explored sales patterns across stores

### 2. Data Preparation
- Converted date columns into datetime format
- Extracted useful time-based features:
  - Year
  - Month
  - Week

### 3. Exploratory Data Analysis
Performed visual analysis to understand:
- Sales trends over time
- Store-wise performance
- Holiday vs Non-Holiday sales
- Top performing stores

### 4. Model Building
Used Random Forest Regressor for forecasting weekly sales.

### 5. Model Evaluation
Evaluated the model using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results

Model Performance:

- MAE: 1432.11
- RMSE: 4010.79
- R² Score: 0.969

The model achieved a high R² score, indicating strong predictive performance on unseen data.

---

## Feature Importance

The model identified the following features as most influential:

1. Department
2. Store
3. Week
4. Month
5. Year
6. Holiday Indicator

---

## Project Structure

FUTURE_ML_01

├── data
│   └── train.csv

├── notebook
│   └── sales_forecasting.ipynb

├── screenshots
│   ├── data_preview.png
│   ├── top_stores.png
│   ├── feature_importance.png
│   └── model_results.png

└── README.md

---

## Key Learnings

Through this project, I gained practical experience in:

- Data preprocessing
- Feature engineering
- Exploratory data analysis
- Machine learning model development
- Model evaluation and interpretation

---

## Author

Rishika Srivastava

Machine Learning Internship Project
