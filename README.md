# 💳 Credit Scoring Predictor

A **Streamlit web app** that predicts an individual’s creditworthiness (Good/Bad) using a machine learning model trained on financial history data.

---

## 📌 Project Highlights

- ✅ **Model**: Random Forest Classifier  
- 🔄 **ML Pipeline**: Preprocessing (OneHotEncoder + StandardScaler)  
- 📊 **Evaluation**: Classification Report, ROC-AUC, ROC Curve  
- 📁 **Deployment**: Streamlit App with `.pkl` pipeline  
- 🎯 **User Interface**: Clean, sidebar-driven input form  

---

## 🚀 Features

- Predict if a customer has **Good or Bad creditworthiness**
- Interactive and attractive **Streamlit UI**
- Accepts 20+ real-world inputs (loan info, employment, savings, etc.)
- Shows **prediction** with **confidence score**
- Feature engineered: `credit_per_month = credit_amount / (duration + 1)`

---

## 🧠 Model Overview

| Component              | Description                                     |
|------------------------|-------------------------------------------------|
| **Dataset**            | `credit-g` dataset from OpenML                  |
| **Algorithm**          | Random Forest Classifier                        |
| **Preprocessing**      | OneHotEncoder (categorical) + StandardScaler    |
| **Feature Engineering**| `credit_per_month`                              |
| **Evaluation**         | ROC-AUC, F1-Score, Precision, Recall            |
| **Exported Model**     | `credit_model.pkl`                              |

---



## 📁 Project Files Description

| File / Folder         | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `app.py`              | Streamlit application file – handles UI, user input, prediction output     |
| `credit_model.pkl`    | Trained ML pipeline with preprocessing + Random Forest model               |
| `requirements.txt`    | List of required Python packages to run the app                            |
| `README.md`           | This documentation file explaining project setup and usage                 |


