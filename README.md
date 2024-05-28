# Loan-Prediction-Classification-Model
This repository contains a machine learning model built to predict loan approval status. The model uses various applicant features to determine the likelihood of loan approval.

# Project Overview
The goal of this project is to create a predictive model that classifies whether a loan will be approved or not based on specific applicant details. The dataset includes features such as applicant income, loan amount, credit history, and more. I used machine learning techniques to build and evaluate different models. The steps involved include descriptive analysis, data preprocessing, and model building using Logistic Regression and Random Forest algorithms.

# Dataset
The dataset used for this project includes the following features:

**ApplicantIncome:** The income of the loan applicant.

**CoapplicantIncome:** The income of the co-applicant (if any).

**LoanAmount:** The amount of the loan requested.

**Loan_Amount_Term:** The term of the loan in months.

**Credit_History:** Credit history of the applicant (1 if the applicant has a credit history, 0 otherwise).

**Gender:** Gender of the applicant.

**Married:** Marital status of the applicant.

**Dependents:** Number of dependents of the applicant.

**Education:** Educational level of the applicant.

**Self_Employed:** Whether the applicant is self-employed.

**Property_Area:** The area where the property is located (Urban, Semi-Urban, Rural).

# Steps Followed 
**Descriptive Analysis** 
- Explored the dataset structure and identified patterns or anomalies.
- Calculated and displayed the schema of the dataset.
- Printed the number of rows and columns.
- Displayed the first few rows of the dataframe.
- Calculated the percentage of missing values for each column.
- Calculated the mean, median, and mode for numerical columns.
- Identified outliers in the numerical columns.
- Plotted the distribution of numerical variables.
- Calculated and displayed the correlation matrix.
- Plotted scatter plots to analyze relationships between variables.

**Data Processing** 
- Calculated the percentage of missing values for each column.
- Imputed missing values in categorical columns using mode.
- Imputed missing values in numerical columns using the median.
- Imputed missing values in the 'Credit_History' column using mode.
- Removed duplicate rows.
- Encoded categorical variables (Gender, Married, Education, Self_Employed, and Loan_Status).

**Model Building**
- Combined all features into a single feature vector using VectorAssembler.
- Built and evaluated a Logistic Regression model.
- Split the dataset into training and testing data.
- Trained the model on the training data.
- Evaluated model performance using accuracy, precision, recall, and ROC curves.
- Built and evaluated a Random Forest model.
- Split the dataset into training and testing data.
- Trained the model on the training data.
- Evaluated model performance using accuracy, precision, recall, F1-score, and ROC curve.
