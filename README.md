# CreditWise_Loan_System


A Machine Learning project that explores applicant financial and personal details to predict whether a loan application is likely to be approved.
Project Overview
Credit Wise uses a loan applicant dataset to explore patterns associated with loan approval and train classification models. The notebook covers data preprocessing, exploratory data analysis (EDA), categorical encoding, feature scaling, model evaluation, and feature engineering.
Objectives
- Understand the factors associated with loan approval.
- Clean and prepare data for machine learning.
- Explore applicant income, credit score, savings, and debt-to-income (DTI) ratio.
- Train and compare classification models using evaluation metrics.
- Explore feature engineering to improve model performance.
Tools & Technologies
- Language: Python
- Data analysis: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn
- Environment: Jupyter Notebook
Workflow
1. Load and inspect data — read the loan dataset and review its structure, summary statistics, and missing values.
2. Handle missing values — impute numerical columns with the mean and categorical columns with the most frequent value.
3. Exploratory Data Analysis — examine loan approval distribution, education level, applicant/co-applicant income, credit score, DTI ratio, and savings.
4. Preprocess categorical data — label-encode selected columns and apply one-hot encoding to other categorical features.
5. Analyze correlations — inspect relationships between numeric features and the target variable.
6. Split and scale data — create training and testing sets and standardize features.
7. Train classification models — evaluate Logistic Regression, K-Nearest Neighbors (KNN), and Gaussian Naive Bayes.
8. Feature engineering — create squared DTI and credit-score features, plus a log-transformed applicant-income feature, then evaluate the models again.
Models Evaluated
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
The notebook evaluates models using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
The notebook identifies Naive Bayes as the best model based on precision in its initial comparison. Actual results may depend on the dataset and preprocessing; see the notebook outputs for metric values.
Dataset
The notebook expects a CSV file named loan_approval_data.csv in the working directory. The dataset should include the columns referenced in the notebook, such as:
- Loan_Approved
- Applicant_ID
- Applicant_Income
- Coapplicant_Income
- Credit_Score
- DTI_Ratio
- Savings
- Education_Level
- Employment_Status
- Marital_Status
- Loan_Purpose
- Property_Area
- Gender
- Employer_Category
