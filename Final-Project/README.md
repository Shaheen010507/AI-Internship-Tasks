# Loan Approval Prediction Using Machine Learning

## Project Overview

This project predicts whether a loan application will be approved or rejected using Machine Learning algorithms. The system analyzes applicant information such as income, education, marital status, credit history, loan amount, and property area to determine loan eligibility.

## Objectives

* Perform data preprocessing and cleaning.
* Conduct Exploratory Data Analysis (EDA).
* Train multiple Machine Learning models.
* Compare model performance.
* Optimize the best model using hyperparameter tuning.
* Predict loan approval status for new applicants.

## Dataset

Dataset: Loan Approval Prediction Dataset

Features:

* Gender
* Married
* Dependents
* Education
* Self_Employed
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Property_Area
* Loan_Status (Target Variable)

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Machine Learning Models

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Handle Missing Values
4. Encode Categorical Features
5. Exploratory Data Analysis
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Hyperparameter Optimization
10. Final Prediction

## Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Results

The trained models were compared using classification metrics. Hyperparameter tuning was applied to improve model performance. The optimized model achieved the highest accuracy and was selected for final prediction.

## Output

The system predicts:

* Loan Approved
* Loan Rejected

based on the applicant's information.

## Future Enhancements

* Web Application Deployment using Streamlit
* Real-Time Loan Prediction API
* Explainable AI Integration
* Cloud Deployment using Azure or AWS

## Conclusion

This project demonstrates how Machine Learning can assist financial institutions in automating loan approval decisions. The developed model provides accurate predictions and helps reduce manual effort while improving consistency in decision-making.
