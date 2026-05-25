# 📊 Customer Churn Analysis and Prediction

![Customer Churn Banner](Customer_churn_banner.jpeg)

## 📌 Project Overview

Customer churn is one of the biggest challenges for telecom companies because losing customers directly affects revenue and increases customer acquisition costs.

This project analyzes customer behavior patterns and builds machine learning models to predict customers who are likely to leave the company.

The project includes:

* 🧹 Data Cleaning & Preprocessing
* 📊 Exploratory Data Analysis (EDA)
* ⚙️ Feature Engineering
* 🤖 Machine Learning Models
* 📈 Model Evaluation
* 💡 Business Insights

---

# 🎯 Project Objectives

* Analyze customer churn behavior
* Identify factors affecting customer retention
* Build predictive machine learning models
* Evaluate model performance using classification metrics
* Generate business-driven insights

---

# 🗂️ Dataset Information

* **Dataset:** Telco Customer Churn Dataset
* **Source:** [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* **Records:** 7,043 customer records
* **Features:** Customer demographics, billing details, internet services, contract type, payment methods, and churn status

---

# 🛠️ Technologies Used

| Category             | Tools                           |
| -------------------- | ------------------------------- |
| Programming Language | Python                          |
| Data Analysis        | Pandas, NumPy                   |
| Data Visualization   | Matplotlib, Seaborn             |
| Machine Learning     | Scikit-learn                    |
| Environment          | Jupyter Notebook / Google Colab |

---

# 🔄 Project Workflow

## 📥 1. Data Collection

* Loaded telecom customer churn dataset from GitHub

## 🧹 2. Data Cleaning

* Removed unnecessary columns
* Converted data types
* Handled missing values

## 📊 3. Exploratory Data Analysis (EDA)

* Customer churn distribution
* Contract type analysis
* Monthly charges distribution
* Correlation heatmap

## ⚙️ 4. Feature Engineering

* Created `AvgChargesPerMonth`
* Created customer tenure groups

## 🔄 5. Data Preprocessing

* One-hot encoding for categorical variables
* Train-test split

## 🤖 6. Machine Learning Models

* Random Forest Classifier
* Logistic Regression

## ⚡ 7. Model Optimization

* Hyperparameter tuning using GridSearchCV

## 📈 8. Model Evaluation

* Accuracy Score
* Classification Report
* ROC-AUC Score
* ROC Curve
* Confusion Matrix
* Feature Importance Analysis

---

# 📌 Key Insights

* 📉 Customers with month-to-month contracts had higher churn rates
* 💰 Higher monthly charges increased churn probability
* ⏳ Long-term customers showed better retention
* 💳 Billing patterns and contract type strongly influenced churn behavior

---

# 🚀 Model Performance

| Model                       | Accuracy  |
| --------------------------- | --------- |
| 🌲 Random Forest Classifier | **79%**   |
| 📘 Logistic Regression      | **80.9%** |

## 📈 ROC-AUC Score

* 🌲 Random Forest ROC-AUC Score: **0.86**

---

# 💡 Business Impact

This project can help businesses:

* 🎯 Identify customers at risk of churn
* 📞 Improve customer retention strategies
* 📉 Reduce revenue loss
* 📊 Make data-driven business decisions

---

# 📂 Repository Structure

```text id="8q2vpk"
customer-churn-analysis/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
├── customer_churn_analysis.ipynb
└── Customer_churn_banner.png
```

---

# 🔮 Future Improvements

* 📊 Power BI Dashboard
* 🌐 Streamlit/Flask Deployment
* 🤖 Additional ML Model Comparison
* 👥 Customer Segmentation Analysis

---

## 👨‍💻 Author

Ritik Kumar Yadav 
M.Tech Student | Aspiring Data Analyst 
Developed as part of M.Tech research and data analytics portfolio.

- LinkedIn: https://www.linkedin.com/in/ritik-kumar-yadav-70a81435a/
- GitHub: https://github.com/RKYEngineering
  
---

## ⭐ If you found this useful, give it a star!
