🚀 Project Overview

This project is an end-to-end Machine Learning web application that predicts the likelihood of heart disease based on clinical health parameters.

It demonstrates the complete ML lifecycle:

Data preprocessing
Exploratory Data Analysis
Model training & evaluation
Model selection
Model serialization
Web integration using Flask
Deployment-ready architecture
The system allows users to input medical features and receive an instant prediction through a web interface.

🎯 Objective

Heart disease is one of the leading causes of mortality worldwide. Early prediction using machine learning can assist healthcare professionals in preventive diagnosis and decision-making.

This project builds a binary classification model to predict:

1 → Heart Disease Present
0 → No Heart Disease

The dataset contains structured patient health records with features such as:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Resting ECG Results
Maximum Heart Rate Achieved
Exercise-Induced Angina
ST Depression
Slope of Peak Exercise ST Segment
Number of Major Vessels
Thalassemia

The target variable indicates the presence of heart disease.

🧠 Machine Learning Pipeline
1️⃣ Data Preprocessing

Handling missing values
Feature selection
Encoding categorical variables (if applicable)
Feature scaling (where required)

2️⃣ Model Training
Multiple algorithms were implemented and compared:
Logistic Regression
Support Vector Machine (SVM)
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)

3️⃣ Model Evaluation
Models were evaluated using:
Accuracy Score
Confusion Matrix
Precision & Recall
Cross-validation

🏗️ System Architecture

User Input (Web Form)
        ↓
Flask Backend (app.py)
        ↓
Load Trained Model (models.pkl)
        ↓
Prediction
        ↓
Display Result

🖥️ Web Application Features

Clean and structured input form
Real-time prediction output
Modular Flask backend
Organized static and template folders
Deployment-ready configuration

Heart-Disease-Prediction/
│
├── app.py
├── Heart-Disease-Prediction.ipynb
├── models.pkl
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   ├── style.css
│   └── result.css
│
└── dataset/

