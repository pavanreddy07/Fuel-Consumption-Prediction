# 🚗 Fuel Consumption Prediction using Machine Learning

A machine learning project to predict the **combined fuel consumption (in L/100 km)** of vehicles using specifications like engine size, transmission type, vehicle class, and fuel type. This project uses data from the Canadian vehicle testing records (2000–2022).

---

## 📊 Dataset Information

- **Dataset**: Fuel Consumption 2000–2022
- **Records**: 22,556
- **Columns**: 13 total (7 selected features + 1 target)

### 🔧 Selected Features:
- `YEAR`: Year of vehicle testing
- `MAKE`: Manufacturer
- `VEHICLE CLASS`: SUV, sedan, compact, etc.
- `ENGINE SIZE`: Engine capacity in liters
- `CYLINDERS`: Number of cylinders
- `TRANSMISSION`: Manual, automatic, etc.
- `FUEL`: Fuel type (gasoline, diesel, hybrid)

### 🎯 Target:
- `COMB (L/100 km)`: Combined fuel consumption

---

## 🎯 Project Objective

To analyze how various vehicle characteristics impact fuel consumption and build predictive models using ML algorithms. The goal is to help manufacturers build efficient vehicles and guide consumers in making eco-friendly decisions.

---

## 🧠 Machine Learning Models Used

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor** ✅ Best Performer
4. **Gradient Boosting Regressor**

---

## 📈 Evaluation Metrics

- **R² Score** (coefficient of determination)
- **Mean Squared Error (MSE)**

### 🏆 Best Model: Random Forest Regressor
- **R² Score**: 0.9579
- **MSE**: 0.35

---

## 🛠️ Implementation Overview

- Data loading and cleaning (using `pandas`)
- Label encoding for categorical values
- Train-test split (80/20)
- Training all four ML models
- Evaluation using MSE and R² Score
- Visualization with `matplotlib`

---

## 📊 Visualization

Bar chart comparing R² scores of all models:
- Random Forest: 🟩 Highest
- Decision Tree: 🟦 Very Good
- Gradient Boosting: 🟪 Good
- Linear Regression: 🟥 Lowest

---

## 📁 Project Structure

