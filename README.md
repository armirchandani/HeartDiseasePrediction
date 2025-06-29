# Heart Disease Prediction

This project involves building a machine learning model to predict the presence of heart disease using the UCI Heart Disease dataset. The dataset includes 303 patient records with 13 clinical features and a binary target variable indicating heart disease presence.

**Dataset:**
Source: UCI Machine Learning Repository
Features: Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise-induced angina, oldpeak, slope, number of major vessels, and thalassemia
Target Variable: 1 indicates presence of heart disease, 0 indicates no disease

**Steps:**

Data Loading and Preprocessing

Loaded dataset using pandas, verified dimensions, and checked for missing values

Conducted exploratory data analysis with .describe() and .value_counts()

Train-Test Split

Split the data into training and testing sets using train_test_split() with stratification

Modeling

Used LogisticRegression from scikit-learn to build the model

Trained on 80% of the dataset and evaluated on the remaining 20%

Model Evaluation

Achieved 85.1% accuracy on training data and 81.9% accuracy on test data

Evaluated model using accuracy_score

Prediction System

Built a user-defined input system to predict heart disease from new patient data
