# 📈 Sales Forecasting using Multiple Models

Sales forecasting using multiple quantitative models: **Seasonal Naïve, Holt-Winters, ARIMA, SARIMA, and Linear Regression**.

## 🎯 Project Objective

The goal of this project was to apply various **quantitative methods** — specifically **time series models** and **causal models** — to forecast the sales of products available in the dataset.

### Key Objectives:
- Perform time series analysis to understand data trends and seasonality
- Apply multiple forecasting models on the training dataset
- Evaluate model performance
- Select the best-performing model for final testing on unseen data

---

## 🧠 Models Covered

1. **Seasonal Naive Model**
2. **Holt-Winters Model (Triple Exponential Smoothing)**
3. **ARIMA Model**
4. **SARIMA (Seasonal ARIMA) Model**
5. **Linear Regression Model**

---

## 📊 Conclusion

We considered different time-series models as well as a regression model for time series forecasting. From our results, we saw that the **Linear Regression Model outperformed** the other time-series models.

### Why did Linear Regression perform better?
- The data showed **strong seasonality** and a **linear trend**
- One of the key assumptions of linear regression — that historical patterns will repeat — held true for this dataset
- Simpler to implement and interpret compared to complex time series models

Thus, for this particular dataset, a **regression-based approach** proved more effective than traditional time-series models for forecasting future sales.

---

## 📁 How to Use This Repository

This repository includes:
- Historical sales data (`CSV`)
- Jupyter notebook with full analysis
- Implementation of all five models
- Evaluation metrics: **MAE**, **RMSE**, **MAPE**

You can run the notebook end-to-end to reproduce the analysis or adapt it for your own sales forecasting needs.

---
