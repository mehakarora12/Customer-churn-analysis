# 📊 Customer Churn Prediction & Analysis

## 📌 Problem Statement
Customer churn is a major challenge for subscription-based businesses. The objective of this project is to analyze customer behavior and build a machine learning model to predict churn, enabling companies to take proactive retention measures.

---

## 📁 Dataset
- Telco Customer Churn Dataset  
- Total records: ~7043 customers  
- Features include:
  - Demographics (gender, dependents)
  - Services (internet, streaming, security)
  - Billing (monthly charges, contract type)
  - Target variable: Churn (Yes/No)

---

## 🧹 Data Preprocessing
- Converted `TotalCharges` to numeric and handled missing values  
- Removed irrelevant columns like `customerID`  
- Applied one-hot encoding to categorical features  
- Performed feature engineering:
  - Created `AverageCharges`
  - Created derived service-based features  

---

## 📊 Exploratory Data Analysis (EDA)
- Analyzed churn distribution  
- Studied impact of:
  - Contract type  
  - Monthly charges  
  - Internet services  
- Used visualizations (countplots, boxplots, heatmaps)

---

## 🤖 Model Building
- Algorithm used: **XGBoost Classifier**
- Handled class imbalance using `scale_pos_weight`
- Train-test split: 80-20

---

## 📈 Model Performance
- Accuracy: ~77%  
- ROC-AUC Score: ~0.82  
- Improved recall for churn class using imbalance handling  

---

## 🔍 Feature Importance (Key Drivers)
Top factors influencing churn:
- Month-to-month contract  
- Fiber optic internet service  
- Lack of technical support and security  
- High monthly charges  
- Streaming service usage  

---

## 💡 Business Insights
- Customers with short-term contracts are more likely to churn  
- High-paying customers require targeted retention strategies  
- Service quality and support significantly impact retention  

---

## 🚀 Business Recommendations
- Promote long-term contracts through discounts  
- Improve fiber optic service experience  
- Offer bundled services (security + support)  
- Target high-risk customers with personalized offers  

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Machine Learning: XGBoost, Scikit-learn  
- Jupyter Notebook  

---

## 📌 Conclusion
This project demonstrates how data analysis and machine learning can be leveraged to identify churn patterns and support data-driven business decisions.
