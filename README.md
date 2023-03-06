# VIX-ID-X-Partners-Predict-Credit-Risk
Predict Credit Risk for Loan Company to reduce the number of Bad Borrowers.

# Feature Engineering
Create Label/Target from Feature loan_status
- There are 9 unique values in 'loan_status' feature.
- For Loan status 'Charged Off', both 'Late', 'Default' and both 'Does not meet the credit policy' status we will consider these borrowers as Bad Borrowers.
- For Loan status 'Current', 'Fully Paid' and 'In Grace Period' we will consider these borrowers as Good Borrowers.
- We will create a new feature 'borrowers_status' containing the value 0 (Good Borrowers) and 1 (Bad Borrowers).

# Data Preprocessing
- Check Duplicated Data
- Handling Missing Value

# Business Analysis
In this section we will try to gain Business Insight from dataset.

# Feature Selection Using Weight of Evidence & Information Value
We will drop some features because :
- Information value <0.02 (useless predictive)
- Information value > 0.5 (suspicious predictive)
- Feature that not make sense to bin

# Feature Encoding
We will encoding several categorical features before we do modeling.

# Modeling
- Split Data Train-Test (70%-30%).
- Find best Model algorithm.
- Confusion Mtarix
- Feature Importance
