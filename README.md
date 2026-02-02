# PRCP-1000-PortugeseBank
Predict whether a customer will subscribe to a term deposit (y) based on their demographic, financial, and campaign-related attributes to help the bank optimize
# Bank Marketing Campaign Prediction – Machine Learning Project

## 📌 Project Overview
This project aims to help a bank’s marketing team identify customers who are more likely to subscribe to a financial product using data analysis and machine learning. By predicting customer subscription probability, the bank can optimize marketing campaigns, reduce costs, and improve conversion rates.

---

## 🎯 Business Problem
Banks spend significant resources on marketing campaigns. Contacting uninterested customers increases operational costs and reduces campaign efficiency.  
The goal is to **predict whether a customer will subscribe to a product** so that marketing efforts can be focused on high-potential customers.

---

## 🧠 Objectives
- Perform Exploratory Data Analysis (EDA) to understand customer behavior
- Identify key features influencing subscription
- Build and compare multiple ML models
- Select the best model based on business-oriented metrics
- Provide actionable recommendations to the marketing team

---

## 📊 Dataset Description
The dataset contains customer demographic, financial, and campaign interaction data such as:
- Age, Job, Education
- Contact type, Campaign duration
- Previous campaign outcomes
- Target variable: `Subscribed (Yes/No)`

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights:
- Customers aged 30–40 show higher subscription rates
- Certain job categories (admin, technician, blue-collar) dominate subscriptions
- Customers with successful previous campaigns are highly likely to subscribe again
- Campaign duration strongly impacts conversion probability

---

## 🛠️ Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Preventing data leakage
- Train-test split

---

## 🤖 Model Building
Models evaluated:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (Final Model)

Evaluation Metrics:
- ROC-AUC
- Precision
- Recall
- Confusion Matrix

**Final Model:** XGBoost  
- ROC-AUC ≈ 0.95  
- Recall ≈ 0.88  

Chosen to maximize identification of potential subscribers.

---

## 💼 Business Recommendations
- Use probability-based targeting instead of binary decisions
- Focus campaigns on high-recall segments
- Prioritize customers with past successful interactions
- Optimize marketing cost by reducing unnecessary outreach

---

## 🚀 Future Improvements
- Hyperparameter optimization using Bayesian Search
- Model deployment via API
- Campaign ROI simulation
- Monitoring model performance over time

---

## 📎 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 👤 Author
Barkam Umesh 
(Data Science & Machine Learning Project)
