# Heart-Diseases-Prediction
Analyzed Heart Disease Data to Predict Risk and Develop Practical Health Solutions
Heart Disease Prediction – Machine Learning Project
## Project Overview

This project applies machine learning models to predict whether a patient is likely to have heart disease based on medical attributes. The dataset includes various patient health indicators, and the goal is to build a reliable classification model that can assist in early diagnosis and prevention.

## Objectives

Perform data preprocessing & cleaning.

Conduct Exploratory Data Analysis (EDA) to identify health factors linked to heart disease.

Train and evaluate multiple classification models.

Compare performance and select the best model for prediction.

## Dataset

Features (typical attributes in heart datasets):

Age

Sex

Chest Pain Type (cp)

Resting Blood Pressure (trestbps)

Serum Cholesterol (chol)

Fasting Blood Sugar (fbs)

Resting ECG (restecg)

Maximum Heart Rate Achieved (thalach)

Exercise Induced Angina (exang)

ST Depression (oldpeak)

Slope, Ca, Thal

Target Variable: target

0 → No Heart Disease

1 → Heart Disease

## Tech Stack

Programming: Python (Jupyter Notebook)

Libraries:

Pandas, NumPy – Data processing

Matplotlib, Seaborn – Visualization

Scikit-learn – ML models & evaluation

## Workflow

Data Preprocessing

Checked for null/missing values.

Standardized/normalized numerical attributes.

Encoded categorical features.

Exploratory Data Analysis (EDA)

Distribution of patients by age, sex, and heart disease outcome.

Correlation heatmap of medical attributes.

Boxplots and pairplots to analyze risk factors.

Modeling

Applied classification models:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Support Vector Machine (SVM)

Hyperparameter tuning with GridSearchCV.

Evaluation

Metrics: Accuracy, Precision, Recall, F1-score.

Confusion Matrix for classification performance.

## Key Insights

Age, cholesterol, resting blood pressure, and maximum heart rate were among the strongest predictors.

Lifestyle-related indicators (exercise-induced angina, chest pain type) significantly impacted risk.

Ensemble methods (Random Forest, Gradient Boosting) gave the best performance.

## Results

Built a reliable classification model to predict heart disease.

Achieved high accuracy and recall, making the model useful for medical risk screening.

Provides explainable insights into which features impact predictions the most.
