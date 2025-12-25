# Loan Prediction Project

## Overview
This project focuses on predicting whether a **loan application will be approved** or not based on applicant details and financial information. It is a classic **binary classification problem** used in the banking and finance domain.

## Dataset Description
The dataset contains the following columns:

| Column | Description |
|--------|-------------|
| Loan_ID | Unique identifier for each loan application |
| Gender | Applicant's gender (Male/Female) |
| Married | Marital status of the applicant (Yes/No) |
| Dependents | Number of dependents |
| Education | Applicant's education level (Graduate/Not Graduate) |
| Self_Employed | Whether the applicant is self-employed (Yes/No) |
| ApplicantIncome | Income of the primary applicant |
| CoapplicantIncome | Income of the co-applicant |
| LoanAmount | Requested loan amount |
| Loan_Amount_Term | Term of the loan in months |
| Credit_History | Credit history (1 = meets guidelines, 0 = does not) |
| Property_Area | Location of the property (Urban/Semiurban/Rural) |
| Loan_Status | Target variable (Y = approved, N = not approved) |

## Objective
The main goal of this project is to **build a predictive model** that can determine the likelihood of loan approval based on applicant demographics, income, credit history, and property details. Accurate predictions can help banks **reduce risk**, streamline loan processing, and make data-driven lending decisions.

## Approach
1. **Data Preprocessing:** Handle missing values, encode categorical features, and scale numerical features.  
2. **Exploratory Data Analysis (EDA):** Understand feature distributions and correlations with loan status.  
3. **Modeling:** Apply machine learning classifiers such as Logistic Regression, Decision Trees, Random Forest, or XGBoost.  
4. **Evaluation:** Use metrics like accuracy, precision, recall, and ROC-AUC to assess model performance.

---

## Results
1.Logistic regression- 85%

2.KNN- k = 7 works really well with 82 % accuracy

3.Random Forest Classifier after hyper parameter tuning: 86% accuracy

4.DL model:

- LR- 0.03 , epochs = 30 gives 78 % accuracy 
- LR - 0.03 ,epochs = 100 gives 75% accuracy
- LR - 0.003 ,epochs = 40 gives- 82 % accuracy
- LR - 0.005 ,epochs = 40 gives- 83 % accuracy
- LR- 0.003 , epochs- 40 gives 83.3 % accuracy
 
 
 ![image](https://user-images.githubusercontent.com/68188457/123515065-b7701c80-d6b3-11eb-9237-7b8eb776756c.png)
