# Heart Disease Prediction

This project aims to predict the presence of heart disease using machine learning techniques, including both supervised and unsupervised learning. It involves analyzing a dataset with various health-related features to predict the likelihood of heart disease in individuals.

## Objective

The goal of this project is to apply both supervised and unsupervised learning methods to classify whether an individual has heart disease or not. The target variable is binary, with values representing the presence or absence of heart disease.

## Dataset

The dataset used in this project is the **Heart Disease Prediction** dataset. It contains information about patients' age, sex, cholesterol levels, blood pressure, chest pain type, electrocardiogram (EKG) results, and other medical features.

### Features

- **Age**: Age of the patient
- **Sex**: Gender of the patient (Male/Female)
- **Cholesterol**: Serum cholesterol level
- **Blood Pressure**: Resting blood pressure
- **Chest Pain Type**: Type of chest pain experienced
- **EKG Results**: Electrocardiogram results
- Other features include exercise-induced angina, st-depression, and more.

### Target

- **Heart Disease Presence (Yes/No)**: This binary classification task involves predicting whether the individual has heart disease.

## Key Steps

### 1. Data Preprocessing

The first step in the process involves cleaning and preprocessing the dataset. This includes handling missing values, encoding categorical features, scaling numerical features, and splitting the data into training and testing sets.

### 2. Training Supervised Learning Model

The next step involves training a supervised learning model to predict the presence of heart disease. For this, algorithms such as **Logistic Regression**, **Support Vector Machines (SVM)**, **Random Forest**, were used. The model will be trained on the labeled dataset to learn the patterns and make predictions then evaluated on their accuracy.

### 3. Training Unsupervised Learning Model

Additionally, unsupervised learning techniques like **K-Means Clustering** can be applied to identify potential patterns in the dataset without the use of labels. The unsupervised model will attempt to group the data based on similar features and offer insights into the underlying structure of the dataset.


