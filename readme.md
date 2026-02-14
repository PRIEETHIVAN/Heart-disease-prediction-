❤️ Heart Disease Prediction using Machine Learning
End-to-End ML + Flask Deployment Project
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

📊 Dataset Details

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

The best-performing model was selected and serialized using Pickle.

models.pkl

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


The Flask application acts as an inference layer between user input and the ML model.

🖥️ Web Application Features

Clean and structured input form

Real-time prediction output

Modular Flask backend

Organized static and template folders

Deployment-ready configuration

🛠️ Tech Stack
🔹 Machine Learning

Python

Scikit-learn

Pandas

NumPy

🔹 Backend

Flask

🔹 Frontend

HTML

CSS

🔹 Model Deployment

Pickle

Gunicorn (for production server)

Render / Railway compatible

📂 Project Structure
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

🚀 Running the Project Locally
Step 1: Clone Repository
git clone https://github.com/your-username/Heart-disease-prediction-
cd Heart-disease-prediction-

Step 2: Install Dependencies
pip install -r requirements.txt

Step 3: Run Application
python app.py


Open in browser:

http://127.0.0.1:5000/

🌍 Deployment

The application can be deployed using:

Render

Railway

PythonAnywhere

Production server example:

gunicorn app:app

📈 Key Highlights for Recruiters

End-to-end ML pipeline implementation

Multiple model comparison & evaluation

Model persistence using Pickle

Flask integration with trained ML model

Clean project structuring

Deployment-ready web application

Demonstrates applied Machine Learning in healthcare domain

🧩 Future Enhancements

Add feature importance visualization

Add SHAP explainability

Add REST API endpoints

Add model retraining pipeline

Docker containerization

CI/CD integration

📌 Learning Outcomes

Through this project, I gained hands-on experience in:

Applied supervised learning

Model evaluation & selection

Backend integration with ML

Web deployment strategies

Real-world healthcare prediction systems

📄 License

This project is built for educational and research purposes.
