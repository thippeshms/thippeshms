# Gold Price Prediction using Machine Learning

## Overview

This project predicts gold prices using Machine Learning based on historical financial market data. The model was developed using the Random Forest Regressor algorithm to analyze the relationship between gold prices and multiple economic indicators such as stock market index values, oil prices, silver prices, and currency exchange rates.

The project demonstrates practical implementation of regression modeling, data analysis, feature engineering, and visualization techniques using Python and Scikit-learn.

---

## Problem Statement

Gold prices are influenced by several economic and financial factors. The goal of this project is to build a Machine Learning model capable of predicting gold prices accurately using historical market data.

---

## Dataset Information

The dataset contains historical financial data with the following features:

| Feature | Description |
|---|---|
| SPX | S&P 500 Index |
| USO | Oil Price |
| SLV | Silver Price |
| EUR/USD | Currency Exchange Rate |
| GLD | Gold Price (Target Variable) |

Dataset Size:
- 2290 rows
- 6 columns

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

### Data Collection and Preprocessing

- Loaded dataset using Pandas
- Checked dataset dimensions and data types
- Verified missing values
- Performed statistical analysis

### Exploratory Data Analysis

Performed correlation analysis between financial indicators and gold prices.

Visualizations included:
- Correlation Heatmap
- Gold Price Distribution Plot
- Actual vs Predicted Price Graph

### Feature Selection

Input Features:
- SPX
- USO
- SLV
- EUR/USD

Target Variable:
- GLD

### Model Building

Implemented Random Forest Regressor to predict gold prices.

Reasons for selecting Random Forest:
- Handles non-linear relationships effectively
- Reduces overfitting
- Provides strong regression performance

### Model Evaluation

The model achieved an R² Score of:

```python
0.9888
```

This indicates excellent prediction accuracy on the testing dataset.

---

## Sample Prediction

### Input

```python
input_data = (1447.160034, 78.470001, 15.1800, 1.471692)
```

### Predicted Gold Price

```python
84.93
```

---

## Key Insights

- Silver prices showed strong positive correlation with gold prices
- Economic indicators significantly influence gold market trends
- Random Forest performed extremely well for regression tasks
- Feature relationships were effectively visualized using heatmaps

---

## Project Structure

```bash
gold_price_prediction/
│
├── data/
│   └── gld_price_data.csv
│
├── model.ipynb
│
└── README.md
```

---

## Results

| Metric | Value |
|---|---|
| Algorithm | Random Forest Regressor |
| R² Score | 0.9888 |
| Task Type | Regression |

---

## Learning Outcomes

This project helped me gain practical experience in:

- Financial data analysis
- Regression modeling
- Data visualization
- Feature engineering
- Machine Learning workflows
- Model evaluation techniques

---

## Future Improvements

Possible future enhancements:
- Hyperparameter tuning
- Time-series forecasting models
- XGBoost implementation
- Streamlit deployment
- Real-time prediction dashboard

---

## Conclusion

This project demonstrates how Machine Learning can be applied to financial prediction problems using historical market data. By leveraging Random Forest Regression, the model successfully predicts gold prices with high accuracy while showcasing end-to-end data science workflow implementation.

## Author

Thippesh Siddappa
