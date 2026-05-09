# Email Spam Detection using NLP and Machine Learning

## Project Objective

The objective of this project is to build an intelligent email classification system capable of detecting spam messages using Natural Language Processing and Machine Learning techniques.

The model classifies emails into:
- Spam
- Ham (Non-spam)

This type of system is widely used in email filtering and cybersecurity applications.

---

## Problem Statement

Email spam is one of the most common problems in digital communication. Spam messages can contain:
- Advertisements
- Fraud attempts
- Phishing links
- Malicious content

Manual filtering is inefficient for large-scale communication systems. This project automates spam detection using machine learning.

---

## Dataset Information

The dataset contains:
- Email Category
- Email Message

Categories:
- Ham
- Spam

Dataset size:
- 5572 email messages

---

## Methodology

### Step 1: Data Loading and Exploration

The dataset was loaded using Pandas and checked for:
- Missing values
- Dataset shape
- Class distribution

### Step 2: Data Preprocessing

Text labels were converted into numerical format:
- Spam = 1
- Ham = 0

### Step 3: Train-Test Split

The dataset was divided into:
- Training data
- Testing data

### Step 4: Text Feature Extraction

TF-IDF Vectorization was used to convert text messages into numerical feature vectors.

This helps the machine learning model understand word importance within emails.

### Step 5: Model Training

A Logistic Regression model was trained using the transformed text data.

### Step 6: Prediction and Evaluation

The trained model was evaluated using accuracy scores on both training and testing datasets.

---

## Machine Learning and NLP Techniques Used

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Logistic Regression

---

## Model Performance

Training Accuracy:
- 96.27%

Testing Accuracy:
- 95.69%

The model achieved strong performance in identifying spam and non-spam emails.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## Project Structure

```text
email_spam_nlp/
│── model.ipynb
│── data/
│     └── mail_data.csv
│── README.md
```

---

## How to Run the Project

Install required libraries:

```bash
pip install pandas numpy scikit-learn
```

Open the notebook:

```text
model.ipynb
```

Run all cells sequentially.

---

## Example Prediction

Input Message:

```text
Free entry in a weekly competition to win prizes
```

Prediction:
- Spam Mail

---

## Real-World Applications

This project can be applied in:
- Email filtering systems
- Fraud detection systems
- Cybersecurity applications
- Messaging platforms

---

## Future Improvements

Possible future enhancements:
- Deep Learning models
- Real-time spam detection API
- Streamlit web application deployment
- Multi-language spam classification

---

## Author

Thippesh Siddappa
