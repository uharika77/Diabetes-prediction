# Diabetes Prediction Using SVM

# Overview

This project aims to predict the likelihood of a person having diabetes based on various health-related features. It utilizes the Support Vector Machine (SVM) algorithm to classify individuals into two categories: diabetic (1) or non-diabetic (0). The dataset used for training and testing contains information on pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age.

# Dependencies

NumPy
Pandas
Scikit-learn (for SVM model)
Data Collection and Analysis

The PIMA Diabetes Dataset is used for this project.
The dataset contains 768 records and 8 features.
Data preprocessing involves standardization using StandardScaler.

# Model Training and Evaluation

The SVM classifier with a linear kernel is used for training.
The model's accuracy is evaluated on both training and test data.
The accuracy achieved on the training data is approximately 78.7%, while on the test data, it's approximately 77.3%.

# Making Predictions

The model can make predictions for new data.
Example predictions are provided in the code for three individuals, along with their respective diabetes status.

# How to Use

Install the required dependencies (NumPy, Pandas, Scikit-learn).
Load the dataset, preprocess it using StandardScaler, and split it into training and testing sets.
Train the SVM classifier with a linear kernel.
Evaluate the model's accuracy.
Use the model to make predictions for new data.
