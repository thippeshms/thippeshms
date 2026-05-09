# Insurance Charges Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Used-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

## Project Overview

This project predicts medical insurance charges using Machine Learning regression models based on demographic and health-related features. The goal is to build an accurate predictive system using historical insurance data.

## Problem Statement

Insurance charges depend on multiple factors such as age, BMI, smoking status, gender, number of children, and region. The objective is to build a regression model that predicts insurance cost accurately.

## Dataset Information

The dataset contains the following features:

| Feature | Description |
|---|---|
| age | Age of the individual |
| sex | Gender |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| region | Residential region |
| charges | Insurance cost (Target variable) |

Dataset size:
- 1338 rows
- 7 columns

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Workflow

### Data Preprocessing
- Handled categorical variables using encoding techniques
- Applied Label Encoding
- Applied OneHot Encoding
- Checked missing values and duplicates
- Scaled numerical features using StandardScaler
- Split dataset into training and testing sets

### Exploratory Data Analysis
- Statistical analysis of dataset
- Correlation analysis
- Feature distribution analysis

### Feature Selection

Input features:
- age
- sex
- bmi
- children
- smoker
- region

Target variable:
- charges

## Machine Learning Models

### Linear Regression
Baseline regression model used for prediction.

### K Nearest Neighbors Regressor
Used for comparison with Linear Regression.

## Model Evaluation

R² Score:

- Linear Regression: 0.7998
- KNN Regressor: 0.2249

Linear Regression performed better and was selected as the final model.

## Sample Prediction

Input:
(19, 0, 27.900, 0, 1, 0)

Output:
25029.64

## Project Structure

Insurance-Charges-Prediction/
│
├── insurance.csv
├── Insurance_Prediction.ipynb
├── requirements.txt
└── README.md

## Installation

Clone the repository:

git clone https://github.com/your-username/Insurance-Charges-Prediction.git

Install dependencies:

pip install -r requirements.txt

Run notebook:

jupyter notebook

## Results

- Best Model: Linear Regression
- R² Score: 0.7998
- Task Type: Regression

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Random Forest and XGBoost models
- Deployment using Flask or FastAPI
- Streamlit dashboard

## Learning Outcomes

- Regression modeling
- Data preprocessing techniques
- Feature engineering
- Model evaluation
- Scikit-learn pipelines
- End-to-end ML workflow

## Author

Thippesh Siddappa
