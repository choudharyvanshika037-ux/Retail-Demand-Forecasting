# Retail-Demand-Forecasting
# 📈 Demand Forecasting using Olist E-Commerce Dataset

## Project Overview

This project focuses on forecasting future product demand using the Olist Brazilian E-Commerce Dataset. Accurate demand forecasting helps businesses optimize inventory management, reduce stockouts, minimize overstocking costs, and improve supply chain efficiency.

The project analyzes historical sales data, customer purchasing patterns, product categories, and seasonal trends to predict future order volumes.

---

## Business Problem

E-commerce companies often face challenges such as:

* Excess inventory leading to higher storage costs
* Stock shortages causing lost sales
* Difficulty planning procurement and logistics
* Seasonal fluctuations in customer demand

The objective of this project is to develop a forecasting model that predicts future demand based on historical sales data.

---

## Dataset

**Source:** Olist Brazilian E-Commerce Public Dataset

The dataset contains:

* Customer information
* Order details
* Product information
* Payment records
* Seller data
* Delivery information

Key tables used:

* `olist_orders_dataset`
* `olist_order_items_dataset`
* `olist_products_dataset`
* `product_category_name_translation`

---

## Project Workflow

### 1. Data Collection

* Loaded multiple Olist datasets
* Merged relevant tables using common keys
* Created a unified sales dataset

### 2. Data Cleaning

* Removed missing values
* Handled duplicate records
* Converted date columns to datetime format
* Filtered invalid transactions

### 3. Exploratory Data Analysis (EDA)

* Monthly sales trend analysis
* Product category demand analysis
* Seasonal pattern identification
* Order volume distribution

### 4. Feature Engineering

Created forecasting features such as:

* Year
* Month
* Quarter
* Day of Week
* Lag Features
* Rolling Average Features

### 5. Model Development

Implemented and compared forecasting models:

* Linear Regression
* Random Forest Regressor
* XGBoost (Optional)
* Time Series Forecasting Models

### 6. Model Evaluation

Performance metrics used:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## Results

The forecasting model successfully identified:

* Seasonal demand patterns
* High-demand product categories
* Monthly sales fluctuations
* Future order volume trends

These insights can help businesses make data-driven inventory and supply chain decisions.

---

## Project Structure

```
Demand-Forecasting-Olist/
│
├── data/
│   ├── raw_data/
│   └── processed_data/
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   └── forecasting_model.ipynb
│
├── images/
│   └── visualizations/
│
├── models/
│   └── trained_models/
│
├── requirements.txt
├── README.md
└── demand_forecasting.py
```

---

## Sample Visualizations

* Monthly Sales Trend
* Top Product Categories
* Seasonal Demand Patterns
* Actual vs Predicted Demand

---

## Future Improvements

* Implement Prophet forecasting model
* Deploy model using Streamlit
* Real-time demand forecasting dashboard
* Product-level demand prediction
* Deep learning models (LSTM)

---

## Conclusion

This project demonstrates how machine learning and time-series analysis can be applied to e-commerce sales data for demand forecasting. The developed forecasting solution provides actionable insights that can improve inventory planning, operational efficiency, and overall business performance.

---

### Author

**Vanshika Choudhary**

Mechanical Engineering Student | Aspiring Data Analyst | Machine Learning Enthusiast
