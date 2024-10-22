# classification-challenge

# Spam Detector
This project demonstrates how to build and compare machine learning models for spam detection using a dataset of email characteristics. Two classification models, logistic regression model and a random forest model were created to fit the provided data, and evaluate which model is more accurate at detecting spam.

# Overview
The code utilizes two algorithms—Logistic Regression and Random Forest Classifier—to classify emails as spam or not spam. The steps include data preprocessing, feature scaling, model training, and evaluation of prediction accuracy.

# Dataset
Source: UCI Machine Learning Repository
Description: Contains 57 features representing word and character frequency in emails, plus a target label (spam).

# Prerequisites
Python 3.x
Libraries: pandas, scikit-learn
# Installation
Install required Python packages

# Data Import and Exploration

Load the dataset using Pandas.
Display the first five rows to confirm successful import.

# Data Preprocessing

Separate features (X) and labels (y), where spam is the target variable.
Split the data into training and testing sets using train_test_split.

# Feature Scaling

Scale the features using StandardScaler for improved model performance.

# Model Training and Evaluation

Train a Logistic Regression model and calculate accuracy on the training and testing datasets.
Train a Random Forest Classifier and compare its accuracy to the Logistic Regression model.

# Evaluation and Results

Output accuracy scores for both models.
Document which model performed better and analyze the results.

# Results
Logistic Regression Accuracy: ~92.7%
Random Forest Accuracy: ~95.5%
The Random Forest model outperformed Logistic Regression, aligning with the prediction that it would handle complex datasets more effectively.
Conclusion
The project showcases the process of building classification models, preprocessing data, and comparing algorithms in a machine learning context. Random Forest showed higher accuracy for spam detection due to its ability to handle feature complexity better.

