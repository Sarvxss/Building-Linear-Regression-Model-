
# 📈 Linear Regression from Scratch in Python

This project demonstrates how to build a **Linear Regression model from scratch**. It walks through cleaning real-world data, understanding the underlying math, and implementing gradient descent for prediction.

---

## 🚀 Project Overview

- 🔨 **Goal**: Predict numerical values (e.g., customer spending) using linear regression.
- 📊 **Dataset Used**: A cleaned and prepared dataset with restaurant attributes (ratings, services, cost, etc.).
- 🔁 **Implemented From Scratch**: Using `numpy` for math operations and `pandas` for data manipulation.
- 📚 **Notebook**: All code is included in a single Jupyter Notebook: `BuildingLinearReggresion.ipynb`.

---

## 🧠 Key Concepts Covered

- Mean Squared Error (MSE) as a cost function
- Gradient Descent algorithm
- Data preprocessing and cleaning
- Feature selection and visualization
- Manual prediction and evaluation

---

## 📦 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
```

Install them via:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 🧼 Data Cleaning Steps

- Removed duplicates and NaN values
- Cleaned columns (rates like `"4.1/5"` → `4.1`, cost fields)
- Standardized features for better gradient convergence

---

## 📈 Model Training

We manually implemented:

- Cost function:
  \[
  MSE = rac{1}{n} \sum (y - \hat{y})^2
  \]
- Gradient Descent:
  - Adjust weights (`m`) and bias (`b`) iteratively
- Prediction:
  \[
  \hat{y} = mx + b
  \]

---

## 📊 EDA and Visualization

We explored:
- Online delivery vs Table booking
- Service type vs Rating
- Restaurant cost distribution
- Location analysis
- Actual vs Predicted values (scatter plot)

---

## 🧠 Learnings

- Better understanding of the internals of linear regression
- Importance of feature scaling and data cleaning
- Visualization as a critical part of model understanding
---

## 🏷️ Tags

`machine-learning` `linear-regression` `python` `data-cleaning` `from-scratch` `gradient-descent` `eda` `restaurant-data`
