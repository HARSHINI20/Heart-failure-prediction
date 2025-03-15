# Heart-failure-prediction
# Heart Failure Prediction using Logistic Regression

## Overview
This project aims to predict the likelihood of heart failure in patients using logistic regression. The dataset includes various clinical features such as age, blood pressure, cholesterol levels, and more. The goal is to build a model that can accurately classify whether a patient is at risk of heart failure.

## Dataset
The dataset used in this project is the [Heart Failure Prediction Dataset](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data) from Kaggle. It contains 299 records with 13 features, including:
- Age
- Anaemia
- High blood pressure
- Creatinine phosphokinase (CPK) level
- Diabetes
- Ejection fraction
- Platelets
- Sex
- Serum creatinine
- Serum sodium
- Smoking
- Time
- Death event (target variable)

## Steps
1. **Data Preprocessing**:
   - Handled missing values (if any).
   - Encoded categorical variables.
   - Scaled numerical features.

2. **Feature Selection**:
   - Selected relevant features using correlation analysis.

3. **Model Training**:
   - Trained a logistic regression model using `scikit-learn`.

4. **Model Evaluation**:
   - Evaluated the model using accuracy, precision, recall, and ROC-AUC score.

## Results
- **Accuracy**: 83.33%
- **Precision**: 0.82
- **Recall**: 0.75


## Requirements
To run this project, you need the following Python libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

