    # 🏦 Loan Prediction Project

This project aims to build a machine learning model that predicts whether a loan applicant will repay their loan or not, based on their financial and personal information. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, and model training using various classification algorithms.

![Credit](https://palankarta.com/wp-content/uploads/2021/01/types-of-credit-facility-img.jpg)

---

## 🔍 Problem Statement

Financial institutions face a major challenge in identifying applicants who are likely to default on their loans. By using historical loan data, we attempt to build a predictive model that can help determine whether or not a loan should be approved.

---

## 📊 Dataset Description

You can access the dataset from the following Kaggle link:
[Loan Prediction Dataset on Kaggle](https://www.kaggle.com/code/smeyra/loan-prediction/input)

The dataset used is `LoansTrainingSet.csv` and includes the following features:

- **Loan ID**: Unique identifier for each loan  
- **Customer ID**: Unique identifier for each customer (a customer may have multiple loans)  
- **Loan Status**: Whether the loan was "Fully Paid" or "Charged Off"  
- **Current Loan Amount**: Amount of the loan taken  
- **Term**: Loan term (Short Term / Long Term)  
- **Credit Score**: Credit rating (0–800 scale)  
- **Years in Current Job**: Time the applicant has been at their current job  
- **Home Ownership**: Rent / Home Mortgage / Own  
- **Annual Income**: Applicant's income  
- **Purpose**: Purpose of the loan  
- **Monthly Debt**: Monthly debt payments  
- **Years of Credit History**: Number of years since first credit activity  
- **Months Since Last Delinquent**: Time since the last late payment  
- **Number of Open Accounts**: Total open credit lines  
- **Number of Credit Problems**: Number of derogatory records  
- **Current Credit Balance**: Total outstanding balance  
- **Maximum Open Credit**: Maximum available credit limit  
- **Bankruptcies**: Number of past bankruptcies  
- **Tax Liens**: Number of tax liens  

---

## ⚙️ Data Preprocessing and Feature Engineering

- Missing values are identified and imputed appropriately.  
- Categorical features are converted into numerical representations.  
- Unnecessary columns such as `Loan ID` and `Customer ID` are dropped.  
- Target variable `Loan Status` is encoded as binary (1: Fully Paid, 0: Charged Off).  

---

## 🧠 Machine Learning Models

Multiple models were trained and evaluated, including:

- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  
- LightGBM Classifier  

Hyperparameter tuning and model comparison were performed to select the best-performing model.

---

## 📈 Model Evaluation Metrics

Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 🧰 Libraries Used

```python
pandas, numpy, seaborn, matplotlib, scikit-learn, xgboost, lightgbm
```

---

## 📌 Results

The trained model helps financial institutions make better decisions by predicting the likelihood of loan default, thus reducing the risk of financial loss.

---
