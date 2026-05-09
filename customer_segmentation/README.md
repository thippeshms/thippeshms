# Customer Segmentation using K-Means Clustering

## Project Objective

The objective of this project is to segment customers into different groups based on their annual income and spending behavior using unsupervised machine learning techniques.

This analysis helps businesses understand customer patterns and improve marketing strategies.

---

## Problem Statement

Retail businesses generate large amounts of customer data, but identifying meaningful customer groups manually is difficult.

This project uses K-Means Clustering to identify hidden customer segments based on spending habits and income levels.

---

## Dataset Information

The dataset contains the following customer attributes:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

For clustering, the following features were selected:

- Annual Income
- Spending Score

---

## Methodology

### Step 1: Data Loading and Exploration

The dataset was loaded using Pandas and checked for:
- Dataset shape
- Data types
- Missing values

### Step 2: Feature Selection

The following features were selected:
- Annual Income
- Spending Score

These features help identify customer behavior patterns.

### Step 3: Finding Optimal Number of Clusters

The Elbow Method was used to determine the optimal number of clusters by calculating WCSS values.

### Step 4: Model Training

K-Means Clustering was applied to group customers into clusters.

### Step 5: Visualization

Customer groups and cluster centroids were visualized using scatter plots.

---

## Machine Learning Technique Used

- K-Means Clustering

K-Means is an unsupervised machine learning algorithm used for grouping similar data points together.

---

## Results

The model successfully identified 5 different customer segments, including:

- High income and high spending customers
- High income and low spending customers
- Low income and high spending customers
- Low income and low spending customers
- Average customers

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Structure

```text
customer_segmentation/
│── model.ipynb
│── data/
│     └── Mall_Customers.csv
│── README.md
```

---

## How to Run the Project

Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

Open the notebook:

```text
model.ipynb
```

Run all cells sequentially.

---

## Output

Add your output visualization screenshot here.

Example:

```md
![Output](output.png)
```

---

## Business Applications

This project can help businesses:
- Understand customer behavior
- Improve targeted marketing
- Increase customer retention
- Support business decision making

---

## Author

Thippesh Siddappa
