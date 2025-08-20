🚗 Vehicle Coupon Recommendation – ML Project
📌 Project Overview

This project aims to build a Machine Learning model that predicts whether a driver will accept a vehicle coupon based on demographic, behavioral, and contextual features.
The dataset contains mixed data types (categorical + numerical), requiring preprocessing and feature engineering before applying classification algorithms.

We experimented with multiple ML models and performed hyperparameter tuning with Optuna to optimize performance.

📂 Project Structure
ML_Project_Vehicle_Coupon_Recommendation.ipynb   # Main notebook
README.md                                        # Project documentation

⚙️ Workflow
1. Data Preprocessing

Handle missing values.

Encode categorical variables using OneHotEncoder.

Scale numerical features with StandardScaler.

Combine using a ColumnTransformer for mixed datatypes.

2. Exploratory Data Analysis (EDA)

Distribution plots, skewness checks.

Correlation heatmap for numerical features.

Value counts for categorical features.

3. Model Training 

Models tested:

Decision Tree

Logistic Regression

Random Forest ✅

Gradient Boosting ✅

SVC

KNN


4. Evaluation Metrics

We evaluated models using:

Accuracy

F1-Score

ROC-AUC

Confusion Matrix

Classification Report

Final evaluation included comparison between Random Forest and Gradient Boosting to pick the best model.


🛠️ Tech Stack

Python

Scikit-learn

Pandas, NumPy

Matplotlib / Seaborn (EDA)
