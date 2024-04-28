# Loan-Approval-Eligibility-Machine-Learning

<p align="center">
  <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--Nbr8xBou--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://miro.medium.com/max/1400/0%2AYEPhDSoA8Q7ec8wv" width="300" height="300">
</p>

# Loan Approval/Eligibility Problem

This project revolves around the data from loan applications. Our goal is to implement a statistical model that predicts whether a loan should be granted to an individual based on the provided dataset. This dataset is a synthetic, anonymized collection designed to mirror the characteristics of real loan application data.

## Project Description

When customers apply for a loan at our company, the decision to grant the loan depends on the likelihood of the loan being repaid. This involves complex determinants and requires extensive statistical analysis and modeling to predict the outcome for each case.

The task is to explore, cleanse, and prepare a dataset of over 100,000 loan records to predict loan eligibility. The outcome is a machine learning model that outputs a unique customer ID along with a loan status label, indicating whether or not the loan should be approved.

## Data Files

The dataset comprises several fields essential for determining loan eligibility:

- **Loan ID**: A unique identifier for the loan information.
- **Customer ID**: A unique identifier for the customer. Note that customers may have multiple loans.
- **Loan Status**: Indicates if the loan was granted.
- **Current Loan Amount**: The loan amount that was either fully paid off or defaulted on. This pertains to previous loans.
- **Term**: Specifies if it is a short-term or long-term loan.
- **Credit Score**: A score between 0 and 800, indicating the borrower's credit risk.
- **Years in Current Job**: Indicates how many years the customer has been in their current job.
- **Home Ownership**: Indicates home ownership status (Rent, Home Mortgage, Own).
- **Annual Income**: The customer's annual income.
- **Purpose**: The purpose of the loan.
- **Monthly Debt**: The customer's monthly payments for existing loans.
- **Years of Credit History**: The number of years since the first entry in the customer’s credit history.
- **Months Since Last Delinquent**: Months since the customer's last delinquent loan payment.
- **Number of Open Accounts**: The total number of open credit cards.
- **Number of Credit Problems**: The count of credit problems in the customer's record.
- **Current Credit Balance**: The total current debt of the customer.
- **Maximum Open Credit**: The maximum credit limit across all credit sources.
- **Bankruptcies**: The number of bankruptcies recorded.
- **Tax Liens**: The number of tax liens.

## Evaluation Criteria

The model must achieve at least a 70% accuracy rate to be considered successful.

This project entails a comprehensive process of data cleaning, feature engineering, model selection, and evaluation to predict loan eligibility efficiently and accurately.

1. [Data Overview](#data-overview)
2. [Importing Libraries](#importing-libraries)
3. [Data Cleaning & Preprocessing](#data-cleaning-and-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Univariate Analysis](#univariate-analysis)
    - [Bivariate Analysis](#bivariate-analysis)
    - [Multivariate Analysis](#multivariate-analysis)
5. [Data Encoding](#data-encoding)
6. [Data Scaling](#data-scaling)
7. [Data Modeling](#data-modeling)
8. [Model Evaluation](#model-evaluation)
9. [Pipeline](#pipeline)
10. [Deployment](#deployment)
