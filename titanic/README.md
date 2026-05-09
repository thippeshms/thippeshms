# TITANIC SURVIVAL PREDICTION USING MACHINE LEARNING

## PROJECT HIGHLIGHT

This project demonstrates a comparative Machine Learning approach to predicting Titanic passenger survival using two different modeling strategies:

- Model 1: Decision Tree Classifier (Baseline Working Model)
- Model 2: Naive Bayes Classifier (Experimental Feature Engineering Approach)

The goal is not just prediction, but to show how different preprocessing and algorithm choices impact model design and performance.

---

## BUSINESS / PROBLEM CONTEXT

The sinking of the Titanic remains one of the most studied disasters in data science. The objective is to predict whether a passenger survived based on attributes such as age, gender, ticket class, and fare.

This project focuses on:
- Data preprocessing strategies
- Model comparison
- Feature engineering impact
- Understanding classification behavior

---

## DATASET OVERVIEW

The dataset includes passenger information:

- PassengerId
- Survived (Target Variable)
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

After preprocessing, only relevant features were retained.

---

## MODEL 1 - DECISION TREE CLASSIFIER (BASELINE MODEL)

### APPROACH

A simple and interpretable machine learning pipeline was built using a Decision Tree Classifier.

### DATA PREPROCESSING

- Removed irrelevant columns
- Handled missing values using mean imputation
- Converted categorical variable (Sex → numerical encoding)

### WHY DECISION TREE?

- Easy interpretability
- Works well with tabular data
- Captures non-linear relationships
- Fast training and prediction

### IMPLEMENTATION FLOW

- Feature selection
- Train-test split
- Model training
- Prediction
- Evaluation

### RESULT

- Training Accuracy: 1.0 (indicates possible overfitting)
- Strong baseline model performance

---

## MODEL 2 - NAIVE BAYES CLASSIFIER (FEATURE ENGINEERING APPROACH)

### APPROACH

This model explores a more structured machine learning pipeline using feature encoding and probabilistic classification.

### DATA PREPROCESSING

- Applied One-Hot Encoding to categorical variables (Sex)
- Combined encoded features into dataset
- Handled missing values using mean imputation

### WHY NAIVE BAYES?

- Works well with probabilistic assumptions
- Efficient for classification problems
- Good baseline for categorical feature-driven datasets

### NOTE ON IMPLEMENTATION

This model highlights an important real-world ML challenge:

- A missing training feature pipeline (`X_train_count`) caused incomplete execution
- Demonstrates importance of correct feature transformation pipeline design

---

## MODEL COMPARISON

| Feature | Model 1 | Model 2 |
|--------|--------|--------|
| Algorithm | Decision Tree | Naive Bayes |
| Approach | Direct encoding | Feature engineering + encoding |
| Complexity | Low | Medium |
| Status | Fully working | Incomplete pipeline |
| Interpretability | High | Medium |
| Learning Insight | Baseline performance | Pipeline design challenges |

---

## KEY INSIGHTS

- Feature engineering significantly impacts model design
- Decision Trees can easily overfit on small datasets
- Naive Bayes requires strict input preprocessing consistency
- Proper pipeline structuring is critical in ML workflows
- Comparing models improves understanding of trade-offs

---

## WHAT THIS PROJECT DEMONSTRATES

This project reflects real-world machine learning thinking:

- Building baseline models first
- Experimenting with alternative algorithms
- Understanding preprocessing impact
- Learning from pipeline errors
- Model comparison mindset

---

## TECHNOLOGIES USED

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## FUTURE IMPROVEMENTS

- Fix Naive Bayes pipeline end-to-end
- Add Logistic Regression and Random Forest comparison
- Perform cross-validation
- Hyperparameter tuning
- Build Streamlit deployment dashboard
- Add feature importance analysis

---

## CONCLUSION

This project demonstrates a structured machine learning workflow by comparing two different modeling approaches on the Titanic dataset. It highlights both successful implementation (Decision Tree) and real-world ML challenges (Naive Bayes pipeline issue), showcasing practical understanding of data preprocessing, model selection, and evaluation.

## Author

Thippesh Siddappa.
