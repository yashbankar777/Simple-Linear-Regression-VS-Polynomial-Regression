# 📘 Simple Linear Regression vs Polynomial Regression  

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Modeling-orange?logo=scikitlearn)  
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow?logo=plotly)  
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-teal?logo=seaborn)  

---

## 📌 Project Overview  

This repository contains a **hands-on implementation and comparison** of  
**Simple Linear Regression** and **Polynomial Regression** using the  
*Real Estate Price* dataset.  

The notebook demonstrates how model complexity affects prediction accuracy,  
highlighting the **Bias-Variance Tradeoff** through real data and visualizations.  

---

## 📂 Notebook Workflow  

### 🔹 1. Data Exploration & Preprocessing  
- Load and inspect the *Real estate* dataset  
- Explore shape, data types, correlations  
- Perform Exploratory Data Analysis (EDA) with `seaborn` & `matplotlib`  

### 🔹 2. Simple Linear Regression  
- Train-test split  
- Model training and prediction  
- Evaluation metrics: **MAE, MSE, RMSE**  

### 🔹 3. Polynomial Regression  
- Feature expansion with `PolynomialFeatures`  
- Train and evaluate polynomial models  
- Compare performance against simple linear regression  

### 🔹 4. Model Evaluation  
- Residual analysis  
- Metrics comparison table (**Linear vs Polynomial**)  
- Visual plots for **underfitting, good fit, overfitting**  

### 🔹 5. Bias-Variance Tradeoff  
- RMSE trends across polynomial degrees  
- Visual plot of **Polynomial Degree vs RMSE**  
- Interpretation of results  

---

## 📊 Results Snapshot  

| Metric | Simple Linear Regression | Polynomial Regression |
|--------|--------------------------|------------------------|
| MAE    | ✅ Lower in Polynomial (if non-linear trend) |  
| MSE    | ✅ Polynomial often improves |  
| RMSE   | ⚖️ Shows bias-variance tradeoff |  

Visualizations included:  
- Heatmaps for correlation  
- Pairplots for feature distributions  
- RMSE vs Degree curve  

---

## 🛠️ Tech Stack  

- **Python** 🐍  
- **NumPy / Pandas** → Data handling  
- **Matplotlib / Seaborn** → Visualization & EDA  
- **Scikit-Learn** → Regression, preprocessing, evaluation  
- **Joblib** → Model persistence  

---

## 🚀 Future Enhancements  

- 🔹 Add **Regularization** (Ridge/Lasso Polynomial Regression)  
- 🔹 Apply **Cross-validation** for degree selection  
- 🔹 Perform **Hyperparameter Tuning** with GridSearchCV  
- 🔹 Extend to **Non-linear Kernels (SVR with RBF kernel)**  

---

## 🎯 Learning Outcomes  

- Understand **difference between linear and polynomial hypothesis functions**  
- Learn how to **choose model complexity** with RMSE trends  
- Grasp **bias-variance tradeoff** via practical example  
- Gain interview-ready explanations with code-backed evidence  

---

