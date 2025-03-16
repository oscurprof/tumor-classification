# Classifying Breast Cancer Tumors: Building a classifier using Logistic Regression

Welcome to my first step into machine learning! A few months ago, I started learning ML with Python, and this project is the result: a logistic regression model to classify breast tumors as Benign or Malignant. It’s been an exciting journey of exploring data, building models, and visualizing results. This repo contains the code, visuals, and lessons from that process.

## Project Overview

Using a breast cancer dataset, I trained a logistic regression model to predict tumor diagnosis based on features like radius, perimeter, and area. The model achieved **90% accuracy**, and I added visualizations to understand the data and evaluate performance. This project marks the beginning of my ML adventure—check it out and let me know what you think!

### Dataset
- **Source**: [IBM Skills Network Cancer Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-BD0231EN-SkillsNetwork/datasets/cancer.csv)
- **Features**: 7 numerical features (e.g., `radius_mean`, `area_mean`, `smoothness_mean`)
- **Target**: Binary classification (`Benign` or `Malignant`)

## Tools & Libraries
- **Python 3.x**
- **pandas**: Data manipulation
- **scikit-learn**: Logistic regression and metrics
- **seaborn & matplotlib**: Data visualization

## Setup
1. **Download "Classification for Tumors.ipynb" File**
2. **Run the file using any suitable IDE e.g. Jupyter, Pycharm, vscode, etc.**
3. **Use Shift+Enter for Execution of a specific Cell**

## Results
-  Accuracy: 90%
-  Classification Report:
   ```bash
               precision    recall  f1-score   support

      Benign       0.90      0.95      0.92       357
   Malignant       0.90      0.82      0.86       212

    accuracy                           0.90       569
   macro avg       0.90      0.88      0.89       569
   weighted avg       0.90      0.90      0.90       569

## What I Learned
-  Cleaning and splitting data into features and targets
-  Training a logistic regression model with scikit-learn
-  Visualizing data and results with seaborn and matplotlib
-  Evaluating models with accuracy, confusion matrix, and ROC curves
