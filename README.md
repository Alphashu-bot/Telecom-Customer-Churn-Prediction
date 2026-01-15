
# Customer Churn Prediction using Machine Learning

## 📌 Project Overview
Customer churn is a major challenge for subscription-based businesses. This project focuses on predicting customer churn using machine learning by analyzing customer behavior, contract details, and service usage patterns.

The goal is to identify customers who are likely to churn and understand the key factors influencing their decision.

---

## 🎯 Objectives
- Predict whether a customer will churn or not
- Analyze the impact of:
  - Customer tenure
  - Contract type
  - Monthly and total charges
  - Service usage patterns
- Compare multiple machine learning models
- Provide business-driven insights to reduce churn

---

## 📊 Dataset Description
The dataset contains customer-level information such as:
- **Demographics**: Gender, senior citizen status
- **Account Information**: Tenure, contract type, payment method
- **Services**: Phone, internet, streaming services
- **Billing**: Monthly charges, total charges
- **Target Variable**: Churn (Yes / No)

---

## 🧠 Machine Learning Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Encoding & Scaling  
4. Model Training  
5. Model Evaluation & Comparison  

---

## 🤖 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting / XGBoost (if applicable)

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

Special focus is given to **recall**, as identifying churned customers is critical from a business perspective.

---

## 🔍 Key Insights
- Customers with **short tenure** are more likely to churn
- **Month-to-month contracts** show significantly higher churn rates
- Higher **monthly charges** correlate with increased churn
- Customers using fewer services are more likely to leave

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Deployment using Flask / FastAPI
- Real-time churn prediction dashboard
- Handling class imbalance with advanced techniques

---

## 📌 Conclusion
This project demonstrates how machine learning can be effectively applied to predict customer churn and generate actionable business insights to improve customer retention.
