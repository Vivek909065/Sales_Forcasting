# 🛒 Walmart Sales & Environmental Predictor

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/ML-Regression-success.svg)
![Licence](https://img.shields.io/badge/license-MIT-red.svg)

An advanced machine learning pipeline designed to forecast not just **Weekly Sales**, but also key environmental and economic indicators: **Temperature** and **Fuel Price**. By understanding the interplay between macro-environmental factors and retail performance, this project provides a 360-degree predictive view for retail analytics.

---

## 📌 Project Overview

Traditional retail forecasting models look at sales in a vacuum. This project takes a multi-dimensional approach by predicting three critical, interdependent targets:

1. **Weekly Sales:** Anticipating demand to optimize inventory and supply chain logistics.
2. **Temperature:** Forecasting localized weather trends to adapt seasonal marketing and product placement.
3. **Fuel Price:** Predicting economic pressures that directly impact consumer foot traffic and logistics costs.

---

## 🚀 Key Features

* **Multi-Output Forecasting:** Independent, optimized pipelines for both economic and environmental target variables.
* **Advanced Feature Engineering:** Extracts temporal patterns (holidays, seasonality, markdown impacts) and store-specific metrics.
* **Robust Data Pipeline:** Handles missing values, scales features dynamically, and manages categorical bottlenecks (Store IDs, Departments).
* **Interactive Visualization:** Evaluation scripts that plot predicted vs. actual trends seamlessly.

---

## 📊 Dataset Insights

The model utilizes historical Walmart dataset features, including:
* **Store & Dept:** Store identifier and department identifier.
* **MarkDown 1-5:** Anonymized data related to promotional markdowns.
* **CPI & Unemployment:** Macroeconomic indicators used to contextualize consumer behavior.
* **IsHoliday:** Evaluation of whether the week contains a major promotional holiday.

---

## 🛠️ Tech Stack

* **Core Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, XGBoost, LightGBM
* **Visualization:** Matplotlib, Seaborn

---

## ⚙️ Installation & Setup

Get the repository up and running locally in just a few steps.

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/walmart-sales-prediction.git](https://github.com/YOUR_USERNAME/walmart-sales-prediction.git)
cd walmart-sales-prediction
