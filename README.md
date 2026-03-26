## Diabetes Prediction using Machine Learning

 Predict whether a patient has diabetes based on medical diagnostic measurements.
 
#  Dataset:

Pima Indians Diabetes Database

768 records, 9 features

 # Features: 
 Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Outcome

# Tools:

Python, pandas, numpy

matplotlib, seaborn

scikit-learn

imbalanced-learn

# Steps:

Load and explore data

Check for missing values and duplicates (none found)

# Exploratory Data Analysis:

Correlation heatmap

Boxplots for outliers

Target distribution (imbalanced: 65% no diabetes, 35% diabetes)

Handle class imbalance using RandomOverSampler

Split data (80% train, 20% test)

# Train 4 models:

Logistic Regression

SVM

Random Forest

Gradient Boosting

Evaluate using accuracy, recall, f1-score

Compare model performance

# Results:

Random Forest: 86% accuracy, 0.87 f1-score (best)

Gradient Boosting: 85.5% accuracy, 0.86 f1-score

Logistic Regression: 74% accuracy

SVM: 69% accuracy

# Best Model:
Random Forest Classifier

