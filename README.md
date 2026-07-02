# 📊 Bank Loan Risk & Interest Prediction using Machine Learning

## 🔍 Project Overview
This project focuses on analyzing borrower data to solve two key financial problems:

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

## ⚠️ Real-World Challenges Addressed
- Handled missing values and inconsistent data formats  
- Detected and treated outliers using IQR method  
- Avoided **data leakage** by removing features used in target creation  
- Performed feature engineering (log transformation, encoding)

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

bank-loan-ml-project/
│
├── data/
│ └── loan_processed_with_classification.csv
│
├── notebooks/
│ ├── eda_regression.ipynb
│ └── classification_pipeline.ipynb
│
├── README.md
├── requirements.txt


---

## 🚀 How to Run

### 1️⃣ Clone Repository
```bash```
git clone https://github.com/your-username/bank-loan-ml-project.git
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

Anmol Agrawal
B.S. Data Science – IIT Madras
B.Tech CSE – GEC Bharatpur
