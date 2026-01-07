#🚗 Car Insurance Claim Prediction

A full-stack machine learning application that predicts whether a car insurance policyholder is likely to make a claim. This project helps insurance companies assess risk, reduce fraudulent claims, and make informed, data-driven decisions.

---

## 📌 Overview

The project leverages machine learning and data preprocessing pipelines to analyze customer and vehicle attributes (e.g., driving history, demographics, credit score) and predict the likelihood of a claim being made. A FastAPI backend serves predictions to a React frontend in real time.

---

## 🎯 Objective

To build a predictive system that can:

- Analyze patterns in customer and vehicle data
- Predict claim approval outcomes
- Support risk assessment and fair premium decisions

---

## ⚙️ Tools & Technologies

### 🧠 Backend
- **Python**, **FastAPI**, **Scikit-learn**, **XGBoost**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Joblib** (for model & preprocessor persistence)

### 💻 Frontend
- **React.js**
- CSS-based responsive UI
- Dynamic feedback system for risk prediction results

### 🔧 Development
- Visual Studio Code
- REST APIs served with **Uvicorn**
- Deployment-ready structure (tested on Render)

---

## 📊 Features

- Predicts insurance claim approval (Approved / Denied)
- Displays risk level and probability with animated confidence bar
- Generates visualizations (correlation heatmaps, ROC curves, claim distribution)
- Handles preprocessing pipeline including imputation, scaling, encoding
- Model training includes Logistic Regression, Random Forest, SVC, XGBoost

---

## 🔄 Process Flow

1. **Data Preprocessing**  
   Missing values handled and features encoded/scaled using `ColumnTransformer`.

2. **Exploratory Data Analysis (EDA)**  
   Visual insights such as:
   - Claim Distribution
   - Driving Experience vs Outcome
   - Feature Correlations

3. **Model Development**  
   Trained multiple classifiers with performance comparison:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - SVC
   - XGBoost

4. **Model Evaluation**  
   Used metrics like Accuracy, Precision, Recall, F1-Score, ROC-AUC for each model.

5. **API & Frontend**  
   - FastAPI serves the ML model as `/predict` endpoint.
   - React frontend accepts user input, sends data to the API, and displays results.

---

## 🚀 How to Run the Project

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

```
 
Summary  
The Car Insurance Claim Prediction project demonstrates how data mining and machine learning can be applied to real-world problems.  
It delivers a practical solution for predicting claim outcomes, supporting better decision-making, and improving the overall efficiency of insurance operations.

Demo
https://github.com/user-attachments/assets/8c2c611e-317a-4211-aff1-e099ad3861bc
