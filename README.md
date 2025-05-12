# Employee Attrition Prediction using Machine Learning

This project aims to predict employee attrition using various machine learning models by analyzing HR-related features such as age, job role, income, and satisfaction levels. The objective is to provide data-driven insights to help organizations reduce turnover and improve employee retention strategies.

## 📊 Dataset Overview

- **Source**: IBM HR Analytics Employee Attrition & Performance dataset  
- **Records**: 1470 employees  
- **Features**: 35 (including demographic, job satisfaction, and performance indicators)  
- **Target Variable**: `Attrition` (Yes/No)

## 🔧 Tools & Libraries Used

- **Programming Language**: Python  
- **Libraries**:  
  - `pandas` – Data manipulation  
  - `numpy` – Numerical operations  
  - `scikit-learn` – Machine learning models and preprocessing  
  - `matplotlib`, `seaborn` – Visualization  
  - `xgboost` – Advanced model training (optional)  
  - `flask` – Web application deployment (if applicable)

## 📌 Project Objectives

- Clean and preprocess employee data for analysis  
- Train and evaluate multiple ML models for attrition prediction  
- Identify key factors influencing employee turnover  
- Deploy the best-performing model for interactive use

## 🔄 Data Preprocessing Steps

1. Handle missing values and constant columns  
2. Encode categorical variables (Label/One-Hot Encoding)  
3. Normalize numerical features  
4. Detect and treat outliers  
5. Address class imbalance if needed  
6. Split dataset into training and testing sets

## 🧠 Machine Learning Models Implemented

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- XGBoost

Each model was evaluated using metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.

## 📈 Methodology

1. Data collection and understanding  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Model training and hyperparameter tuning  
5. Performance evaluation and model selection  
6. Deployment (optional: Flask app)

## 🗂️ Folder Structure
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for EDA and model building
├── models/ # Trained model files (Pickle, etc.)
├── app/ # Flask web app files (if applicable)
├── requirements.txt # Python dependencies
└── README.md # Project documentation


