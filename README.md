# loan-approval-ml
PDS Final Project - Predicting Loan Approvals using Machine Learning

# 🏦 Data-driven Loan Approval: A Machine Learning Approach

This project uses machine learning to predict whether a loan should be approved based on applicant details. It was developed as a final project for the **Practical Data Science** course at **Pace University**, showcasing a full pipeline from data exploration to model development and business recommendations.

---

## 📌 Problem Statement

Traditional loan approval processes are often manual, slow, and inconsistent—leading to customer dissatisfaction and financial risks due to incorrect approvals or rejections. Our goal is to create a **data-driven solution** that improves accuracy, reduces risk, and supports fair decision-making.

---

## 🔍 Project Overview

- **Project Title:** Data-driven Loan Approval: A Machine Learning Approach  
- **Course:** Practical Data Science  
- **Model Used:** Logistic Regression  
- **Accuracy:** 79.8%  
- **Primary Metric Focus:** High Recall (99%) – minimizes false rejections

---

## 📂 Repository Structure

loan-approval-ml/ │ ├── data/ # 📊 Raw datasets used for training/testing │ ├── train.csv │ └── test.csv │ ├── notebook/ # 🧠 Jupyter notebook with all code │ └── PDSfinaltrial.ipynb │ ├── presentation/ # 🖼 Final presentation slides │ └── DATAEDAphase2pptfinalpresented.pdf │ └── README.md # 📘 Project overview and documentation


---

## 🧠 Modeling Approach

- **Binary Classification Problem:** Predict whether a loan application will be approved (`Yes` or `No`)
- **Model Chosen:** Logistic Regression
  - Simple, interpretable, and performs well on small datasets
  - Probability-based predictions
- **Key Features:**
  - Applicant & Co-applicant income
  - Loan amount & term
  - Credit history
  - Marital status, dependents, property area

---

## 📊 Key Findings

- **Credit History** is the strongest predictor of loan approval
- **Married** applicants and those from **semiurban** areas are more likely to be approved
- Higher income increases loan approval probability, but income alone is not enough
- Logistic Regression achieved:
  - **Accuracy:** 79.8%
  - **Precision:** 83%
  - **Recall:** 99%
  - **F1-Score:** 76%

---

## ✅ Business Recommendations

- Introduce manual validation for high-risk applicants (to catch false positives)
- Collect additional data (e.g., debt-to-income ratio) for better prediction accuracy
- Deploy the model in a **pilot environment** and monitor for model drift

---

## 🛠 Technical Next Steps

- Tune decision thresholds to reduce false positives
- Explore advanced models like Random Forest or XGBoost
- Continuously monitor and retrain the model using new application data

---

## 📎 Data Source

- Kaggle Loan Dataset:  
  [Loan Eligibility Prediction using Machine Learning](https://www.kaggle.com/code/johnpaulchikwe/loan-eligibility-prediction-using-machine-learning)




