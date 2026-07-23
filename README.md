# 🌾 Applied Data Mining with Python

A comprehensive data mining project applying supervised learning, time series forecasting, and unsupervised learning techniques to solve predictive analytics problems across multiple real-world inspired domains.

---

## Project Overview

This project demonstrates the application of several data mining techniques using Python through three independent case studies. Each dataset represents a different analytical problem and requires specific preprocessing, modeling, and evaluation strategies.

The notebook covers the complete analytical workflow, including data cleaning, feature engineering, predictive modeling, feature selection, time series forecasting, and unsupervised learning.

---

## Case Studies

### 🌾 Agricultural Analytics

Predict crop yield and identify severe pest outbreaks using environmental, agronomic, and soil-related variables.

Tasks include:

- Regression analysis for crop yield prediction.
- Binary classification for severe pest detection.
- Feature selection and model evaluation.

---

### 🚁 Drone Operations

Predict the energy consumption of drone deliveries using operational and environmental variables such as payload, route characteristics, weather conditions, and maintenance indicators.

---

### 📈 Industrial Production Forecasting

Forecast the Spanish Industrial Production Index (IPI) using classical time series forecasting techniques.

Models include:

- Holt-Winters Exponential Smoothing
- SARIMAX

---

## Techniques Applied

### Data Preparation

- Missing value treatment
- Outlier detection
- Feature transformation
- Data preprocessing

### Supervised Learning

- Multiple Linear Regression
- Logistic Regression
- Feature Selection
  - LASSO
  - Sequential Feature Selection
  - Cramér's V

### Model Evaluation

- Cross-validation
- Performance metrics
- Model comparison

### Time Series Forecasting

- Holt-Winters
- SARIMAX

### Unsupervised Learning

- Correlation Analysis
- K-Means Clustering
- Dimensionality Reduction

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Matplotlib
- Seaborn

---

## Repository Structure

```text
.
├── Applied_Data_Mining.ipynb
├── datasets/
│   ├── Datos_agricultura.csv
│   ├── Datos_drones.xlsx
│   └── IPI_Esp.xlsx
├── requirements.txt
└── README.md
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels
jupyter
```
