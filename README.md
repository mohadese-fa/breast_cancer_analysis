# Breast Cancer Detection - Machine Learning

This project utilizes machine learning techniques to detect breast cancer using the Breast Cancer Wisconsin (Diagnostic) dataset. The models used for classification are Random Forest and Support Vector Machine (SVM).

## Project Goal
Identify benign and malignant breast cancer using features like Clump Thickness and other medical attributes. The goal is to classify patients into "cancer" and "non-cancer" categories.

## Data
The dataset is from [Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/marshuu/breast-cancer), and contains diagnostic features such as:
- Clump Thickness
- Uniformity of Cell Size
- Uniformity of Cell Shape
- Marginal Adhesion
- Single Epithelial Cell Size
- Bare Nuclei
- Bland Chromatin
- Normal Nucleoli
- Mitoses

## Process Overview
1. **Data Preprocessing**: Loading, cleaning, and splitting the dataset into training and test sets.
2. **Model Training**: Training Random Forest and SVM models for classification.
3. **Model Evaluation**: Performance evaluation using confusion matrices and heatmaps.

## Results
- **Random Forest**: An ensemble method that uses multiple decision trees for accurate predictions.
  - *Confusion Matrix*: Analyzed to understand the number of correct and incorrect predictions (TP, TN, FP, FN).
  
- **SVM**: A classical machine learning algorithm that separates data with a hyperplane.
  - *Confusion Matrix*: Used to evaluate the model's performance and identify areas for improvement.
