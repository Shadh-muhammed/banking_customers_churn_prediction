# 📊 Banking Customer Churn Prediction Using Machine Learning

## 🚀 Project Overview
This project builds an end-to-end machine learning pipeline to predict customer churn in a banking dataset. The goal is to identify customers who are likely to leave, enabling proactive retention strategies and better business decisions.

---

## 🎯 Problem Statement
Customer churn is a major challenge in banking. Retaining existing customers is more cost-effective than acquiring new ones. This project aims to:
- Predict customer churn accurately
- Identify key factors driving churn
- Provide actionable business insights

---

## 📂 Dataset
The dataset includes customer information such as:
- Credit Score  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- Number of Products  
- Credit Card Ownership  
- Activity Status  
- Estimated Salary  

---

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🔍 Project Workflow

### 1. Data Preprocessing
- Removed irrelevant columns (RowNumber, CustomerId, Surname)
- Encoded categorical variables using One-Hot Encoding
- Scaled numerical features where required

---

### 2. Exploratory Data Analysis (EDA)
Key findings:
- Older customers are more likely to churn  
- Inactive members have a significantly higher churn rate  
- Customers with 3–4 products show very high churn  
- Germany has the highest churn rate among regions  

---

### 3. Feature Engineering
Created new features to improve model performance:
- Balance per Product  
- Salary-to-Balance Ratio  
- Age Groups and Tenure Buckets  
- High Product Risk Indicator  

---

### 4. Model Building
Trained multiple models:
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- AdaBoost  

---

### 5. Model Evaluation
Evaluation metrics used:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

---

## 📈 Model Performance (Best Model: Gradient Boosting)

| Metric | Score |
|--------|------|
| Accuracy | 0.868 |
| Precision | 0.780 |
| Recall | 0.489 |
| F1 Score | 0.601 |
| ROC-AUC | 0.869 |

---

## 🔑 Key Insights
- Age and number of products are the most important predictors of churn  
- Inactive customers are more likely to leave  
- Customers in Germany have higher churn rates  
- Engineered features added additional predictive value  
- Tree-based models performed better than linear models  

---

## ⚠️ Model Limitation
- Recall for churn is relatively low (49%), meaning some churners are missed  
- Model is conservative (fewer false positives but misses some true churn cases)  

---

## 💼 Business Impact
- Helps identify high-risk customers early  
- Enables targeted retention strategies  
- Reduces potential revenue loss  
- Improves decision-making  

---

## 🧠 Conclusion
This project demonstrates how machine learning can be used to predict customer churn and generate actionable insights. It combines strong EDA, feature engineering, and model evaluation to deliver a practical business solution.

---

## 🚀 Future Improvements
- Hyperparameter tuning  
- Threshold optimization to improve recall  
- Model deployment (web app/dashboard)  
- Real-time prediction integration  
