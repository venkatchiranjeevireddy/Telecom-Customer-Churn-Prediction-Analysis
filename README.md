# 📊 Telecom Customer Churn Prediction & Analysis

## 📌 Project Overview

This project focuses on analyzing customer behavior and predicting churn in a telecom company using machine learning.

Customer churn refers to customers who stop using a company's service. Identifying such customers early helps businesses take proactive steps to improve retention.

### 🎯 Objectives:

* Perform **data cleaning and preprocessing**
* Conduct **Exploratory Data Analysis (EDA)**
* Build **classification models** to predict churn
* Evaluate models using appropriate metrics
* Derive **business insights to reduce churn**

---

## 🔗 Dataset Source

Dataset used in this project:

👉 https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## 📂 Features in Dataset

Some key features include:

* `tenure` → Number of months customer has stayed
* `MonthlyCharges` → Monthly bill amount
* `TotalCharges` → Total amount spent
* `Contract` → Type of contract (Monthly / Yearly)
* `PaymentMethod` → Payment type
* `InternetService` → Type of internet service
* `Churn` → 🎯 Target variable (Yes/No)

---

## 🧹 Data Cleaning & Preprocessing

* Handled missing values in `TotalCharges`
* Converted categorical variables using encoding
* Removed unnecessary columns (`customerID`)
* Ensured proper data types for modeling

---

## 📊 Exploratory Data Analysis (EDA)

### Key Analyses:

* Churn distribution
* Tenure vs churn
* Monthly charges vs churn
* Contract type vs churn
* Payment method impact on churn

### 📈 Key Insights:

* Customers with **month-to-month contracts** churn more
* **Higher monthly charges** increase churn probability
* Customers with **longer tenure** are less likely to churn
* Certain payment methods show higher churn rates

---

## 🤖 Machine Learning Models

### Models Used:

* Logistic Regression (Baseline Model)
* Random Forest Classifier

### 📊 Evaluation Metrics:

* Precision
* Recall
* F1-score
* ROC-AUC

> ⚠️ Recall is important as the goal is to correctly identify customers who are likely to churn.

---

## 📊 Feature Importance

Top factors influencing churn:

* Contract type
* Tenure
* Monthly charges

---

## 💡 Business Insights

* Focus on **month-to-month customers** with retention offers
* Improve pricing strategies to reduce churn due to high charges
* Target **new customers early**, as they are more likely to churn
* Encourage long-term contracts to improve retention

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 How to Run

```bash
# Clone repository
git clone <your-repo-link>

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Run script
python churn_project.py
```

---

## 💡 Conclusion

This project demonstrates how machine learning can be used to identify customers at risk of churn and provide actionable insights for improving customer retention.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
