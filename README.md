# 🚗 Used Car Price Prediction - India (Cardekho Dataset)

A machine learning project to predict the selling price of used cars in India based on various features such as brand, mileage, age, fuel type, and more. This model is trained on real-world data from Cardekho.com.

---

## 📌 Problem Statement

The used car market in India is dynamic and inconsistent. Sellers often struggle to price their cars accurately due to multiple influencing factors like mileage, fuel type, brand, and age. Our goal is to create a reliable ML model that predicts a fair selling price for used vehicles.

---

## 🎯 Objective

To build a machine learning model that predicts the price of a used car based on its features. The solution will help:

- ✅ Sellers list their cars at optimal prices.
- ✅ Buyers find fair deals.
- ✅ Improve overall transparency in the Indian used car marketplace.

---

📦 Requirements
> Python 3.7+
> Pandas
> NumPy
> Matplotlib / Seaborn
> scikit-learn
> Jupyter Notebook

## 📊 Dataset Overview

- **Source**: Cardekho.com
- **Rows**: ~8000+
- **Features**:
  - `car_name`, `brand`, `model`, `vehicle_age`
  - `km_driven`, `fuel_type`, `transmission_type`, `engine`, `seller_type`
  - `mileage`, `max_power`, `seats`
  - Target: `selling_price`

---

## 🧪 Machine Learning Workflow

- Exploratory Data Analysis (EDA)
- Feature Engineering & Encoding
- Feature Scaling
- Model Training (Linear Regression, Ridge, Lasso, Random Forest)
- Evaluation Metrics: RMSE, R² Score
- Model Comparison and Selection

---

## 📈 Best Model

- **RandomForestRegressor** was selected as the best performing model based on R² Score and RMSE.

---

## 🛠️ Setup Instructions

1. Clone this repository:
   
   git clone https://github.com/KomalPL/CarDekho-Price-Prediction

2. Install dependencies:

pip install -r requirements.txt

3. Launch the notebook:

jupyter notebook

4. Open Used Car Price Prediction.ipynb and run all cells.
