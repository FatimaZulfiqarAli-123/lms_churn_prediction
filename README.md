# 📘 LMS Churn Prediction System
---
## 📌 Project Overview
This project predicts whether users of a Learning Management System (LMS) are likely to **churn (stop using the platform)** based on their engagement behavior.

Using machine learning models like **Random Forest** and **Gradient Boosting**, the system analyzes user activity patterns and identifies **at-risk learners early**, enabling proactive intervention.

---

## 🎯 Objective
- Predict user churn in an LMS platform  
- Identify key behavioral factors affecting churn  
- Help institutions improve student engagement and retention  
- Provide a ranked list of users likely to leave  

---

## ⚙️ Technologies Used

- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- SHAP (Explainability)  
- Joblib (Model saving)

---

## 🤖 Machine Learning Models

- Random Forest Classifier 🌲  
- Gradient Boosting Classifier 🚀  

---

## 📈 Workflow

1. Data Generation / Loading  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Train-Test Split  
5. Model Training  
6. Model Evaluation  
7. Feature Importance Analysis  
8. SHAP Explainability  
9. Prediction of At-Risk Users  
10. Model Saving  

---

## 🚨 Output

The system outputs:

- Model accuracy scores  
- Confusion matrix  
- ROC curve  
- Feature importance graph  
- SHAP summary plot  
- **List of users likely to churn (user_id + probability)**  

### Example Output:
🚨 USERS MOST LIKELY TO CHURN:

user_id churn_probability

102       0.89

245       0.85

311       0.81
