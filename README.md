❤️ Heart Disease Prediction System using Ensemble Machine Learning

A Machine Learning-based Heart Disease Prediction System built using the Framingham Heart Study Dataset. The project predicts the risk of developing coronary heart disease (CHD) within the next 10 years using advanced feature engineering, data balancing techniques, and ensemble learning models.

📌 Project Overview

This project analyzes patient health records and predicts the likelihood of developing heart disease over the next decade.

The system:

Cleans and preprocesses medical data
Handles missing values using KNN Imputation
Creates engineered health features
Balances data using SMOTE
Selects important features
Trains multiple machine learning models
Builds a Voting Ensemble model
Evaluates performance using ROC-AUC and Cross Validation
Generates patient risk reports
Sends automated email notifications
🚀 Features
Data Preprocessing
KNN Imputation for missing values
Feature scaling using StandardScaler
Train-Test Split
Feature Selection using SelectKBest
Feature Engineering

Custom health indicators:

Blood Pressure Ratio
Pulse Pressure
Cholesterol Ratio
Age × BMI
Age × Glucose
BMI × Glucose
BP Pulse Features

These features improve prediction accuracy.

Handling Class Imbalance

The Framingham dataset contains imbalanced classes.

SMOTE is used to:

Oversample minority class
Improve model learning
Reduce prediction bias
🤖 Machine Learning Models
Logistic Regression

Used as a baseline classification model.

Random Forest

Optimized with:

800 Trees
Balanced Class Weights
Tuned Depth and Split Parameters
XGBoost

Configured with:

1200 Trees
Learning Rate = 0.02
Max Depth = 6
Regularization
Voting Ensemble

Combines:

Logistic Regression
Random Forest
XGBoost

Using Soft Voting to improve prediction accuracy.

📊 Model Evaluation

The project evaluates models using:

Accuracy Score
Cross Validation
ROC-AUC Score
Classification Report
Confusion Matrix
📂 Dataset
Framingham Heart Study Dataset

Target Variable:

TenYearCHD
0 → No Heart Disease Risk
1 → High Risk of Heart Disease within 10 Years

Dataset includes features such as:

Age
Gender
Smoking Status
Blood Pressure
Cholesterol
Diabetes
BMI
Heart Rate
Glucose Level
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-Learn
XGBoost
Imbalanced-Learn (SMOTE)
Matplotlib
SMTP Email Service
Jupyter Notebook
📈 Project Workflow
Dataset
   ↓
KNN Imputation
   ↓
Feature Engineering
   ↓
Feature Scaling
   ↓
Feature Selection
   ↓
SMOTE Balancing
   ↓
Model Training
   ↓
Voting Ensemble
   ↓
Evaluation
   ↓
Risk Prediction
   ↓
Email Report
📧 Email Notification System

After prediction, the system automatically sends:

Patient Risk Status
Probability Score
Health Recommendations

to:

Patient Email
Doctor Email

using Gmail SMTP.

🎯 Sample Prediction
Patient Age: 52

Risk Probability: 82%

Prediction:
High Risk of Heart Disease

Recommendations:
✔ Regular Exercise
✔ Healthy Diet
✔ Reduce Smoking
✔ Monitor Blood Pressure
✔ Routine Medical Checkups
⚙️ Installation
Clone Repository
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
Install Dependencies
pip install pandas numpy scikit-learn
pip install xgboost
pip install imbalanced-learn
pip install matplotlib
Run Notebook
jupyter notebook




dataset :https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression?utm_source=chatgpt.com
Open:

Fina_MIN.ipynb
📁 Project Structure
Heart-Disease-Prediction/
│
├── Fina_MIN.ipynb
├── framingham dataset.csv
├── README.md
│
├── Model Training
├── Feature Engineering
├── Ensemble Learning
├── Prediction System
└── Email Alert Module
👨‍💻 Author

Sanjay Gandhi

Machine Learning Project for Predicting 10-Year Heart Disease Risk using Ensemble Learning, Feature Engineering, SMOTE, and XGBoost.

📜 Disclaimer

This project is intended for educational and research purposes only. Predictions should not be considered professional medical advice or diagnosis.
