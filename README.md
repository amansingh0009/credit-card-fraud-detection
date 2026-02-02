# Credit Card Fraud Detection System

## Overview
This project implements a supervised machine learning pipeline to detect fraudulent credit card transactions.
The primary objective is to minimize false negatives by optimizing Recall and F1-Score, which is critical in fraud detection systems.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib / Seaborn

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Neural Network (MLPClassifier)

## Key Features
- Data preprocessing and feature scaling
- Feature engineering for improved model performance
- Handling severe class imbalance using SMOTE and undersampling
- Model evaluation using Recall, Precision, F1-Score, ROC-AUC, and Confusion Matrix
- Focus on minimizing false negatives in fraud detection

## Dataset
Due to GitHub file size limitations, the dataset is not included in this repository.

You can download the dataset from Kaggle:
https://www.kaggle.com/mlg-ulb/creditcardfraud

After downloading, place the file at:

## How to Run the Project
1. Clone the repository
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
jupyter notebook
EDA+ML.ipynb


Credit-Card-Fraud-Detection-Project/
│
├── Datasets/               # Dataset folder (ignored in GitHub)
├── EDA+ML.ipynb            # Exploratory Data Analysis & Model Training
├── credit_card_fraud_detection_code.ipynb
├── requirements.txt
├── Solution-Approach.pdf
├── README.md
└── .gitignore
