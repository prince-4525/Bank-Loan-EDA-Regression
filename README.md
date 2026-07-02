# 📊 Bank Loan Risk & Interest Prediction using Machine Learning

## 🔍 Project Overview
This project demonstrates Exploratory Data Analysis (EDA) and Machine Learning techniques on a bank loan dataset. It includes data preprocessing, visualization, regression modeling, and loan approval prediction.

- **Interest Rate Prediction (Regression)**
- **Loan Approval Prediction (Classification)**

The project simulates a real-world lending scenario by combining **statistical modeling (OLS)** with a **machine learning pipeline** to support data-driven credit decisions.

---

## 📁 Dataset
- Records: **2,500+ borrowers**
- Features include:
  - FICO Score
  - Loan Length
  - Debt-to-Income Ratio
  - Credit Inquiries
  - Loan Purpose & Ownership

---


## ⚙️ Key Tasks Performed

### 📊 1. Exploratory Data Analysis (EDA)
- Analyzed feature distributions and correlations  
- Identified key risk indicators  

### 📉 2. Regression Modeling
- Built **OLS regression model**
- **R² Score:** 0.77  
- **MAPE:** 12.29%  
- Used for interest rate prediction  

### 🤖 3. Classification Modeling
- Created a **loan approval target** based on financial logic  
- Trained multiple models:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  

### ⚙️ 4. Model Optimization
- Applied **GridSearchCV** for hyperparameter tuning  
- Selected best model based on performance  

---

## 📈 Model Performance

### 🔹 Regression (OLS)
- R² Score: **0.77**
- MAPE: **12.29%**

### 🔹 Classification (Random Forest - Tuned)
- Accuracy: **98.2%**
- Balanced precision, recall, and F1-score  

---

## 🔑 Key Insights
- **FICO score** is the strongest predictor of creditworthiness  
- Higher **debt-to-income ratio** increases risk  
- Loan length and credit inquiries influence interest rates  
- Proper preprocessing significantly improves model performance  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Statsmodels  

---

## 📦 Project Structure

Bank-Loan-EDA-Regression/
│
├── Exploratory Data Analysis & Regression Modeling.ipynb
├── 2_final_loan_ml_pipeline.ipynb
├── LoansData (1).csv
├── loan_processed_with_classification.csv
├── requirements.txt
└── README.md

---

## 🚀 How to Run

### 1️⃣ Clone Repository
```bash```
git clone https://github.com/prince-4525/Bank-Loan-EDA-Regression.git
cd bank-loan-ml-project
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run Notebook
jupyter notebook
🧠 Key Learnings
Handling real-world messy financial data
Feature engineering and transformation techniques
Avoiding data leakage in ML pipelines
Model comparison and hyperparameter tuning
Applying ML to real-world financial decision-making
🎯 Use Cases
Credit risk assessment
Loan approval systems
Financial analytics and decision support
Portfolio / internship project
👤 Author

Prince Chaurasia
B.Tech CSE Graduate
Email: inprincechaurasia@gmail.com
GitHub: https://github.com/prince-4525
LinkedIn: https://www.linkedin.com/in/prince-chaurasia-bb0a852a1/
