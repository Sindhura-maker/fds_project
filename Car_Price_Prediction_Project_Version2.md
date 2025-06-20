# 🚗 **CAR PRICE PREDICTION USING DATA SCIENCE**

This Data Science project focuses on developing a **regression model to predict the resale value of used cars**. It includes detailed steps from data cleaning to model evaluation, all using real-world automobile data. The aim is to help buyers and sellers understand the **fair market value** of a car based on its features.

---

## 📌 **DATASET SOURCE**

The dataset is sourced from **Kaggle** or similar public data repositories and contains features such as:

- **Car Brand, Model, Year**
- **Fuel Type, Transmission, Owner Type**
- **Mileage, Engine Size**
- **Location**, and more

---

## 🎯 **TARGET VARIABLE**

**PRICE** – The resale value of the car (**continuous numerical value**)

---
DATASET LINK:
https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

---

## 🎯 **OBJECTIVE**

- **Perform Exploratory Data Analysis (EDA)** to discover key patterns in the data
- **Preprocess data** with encoding, null value treatment, and feature engineering
- **Train regression models** to predict car price accurately
- **Evaluate models** using performance metrics like **R² Score** and **MSE**
- **Apply the trained model** to predict car prices for new/unseen data

---

## 📊 **DATA SCIENCE WORKFLOW**

### 1️⃣ **DATA LOADING & INSPECTION**
- Read `.csv` file using **pandas**
- Inspect dataset structure: `head()`, `info()`, `shape`, `describe()`

### 2️⃣ **DATA CLEANING**
- Handle **missing values** (if any)
- Remove **irrelevant or duplicate records**
- Encode categorical variables using **LabelEncoder**

### 3️⃣ **EXPLORATORY DATA ANALYSIS (EDA)**
- Visualize **correlation heatmap** using **seaborn**
- Analyze **price trends** by year, brand, fuel type, etc.
- Identify **outliers** using **boxplots**

### 4️⃣ **FEATURE SELECTION**
- Select **features with strong influence** on price
- Remove **multicollinearity** if detected

### 5️⃣ **MODEL BUILDING**
- Use `train_test_split()` for splitting training and testing data
- Fit **XGBoost Regressor** to training data

### 6️⃣ **MODEL EVALUATION**
- Use:
  - `from sklearn.metrics import mean_squared_error, r2_score`
  - **R² Score** – Goodness of fit
  - **Mean Squared Error (MSE)** – Penalty for prediction error

### 7️⃣ **PREDICTIONS**
- Model can **predict prices for new cars** based on user input

---

## 📈 **MODEL PERFORMANCE**

- **Best model:** XGBoost Regressor
- **High R² Score** and **low MSE**
- **Capable of predicting a wide range of car prices with high accuracy**

---

<div align="right"><b>- Chilukuri Sindhura Reddy</b></div>
