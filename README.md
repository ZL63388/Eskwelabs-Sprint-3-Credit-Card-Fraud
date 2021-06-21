# Credit Card Fraud Detection

This project was created as part of the Eskwelabs Data Science Fellowship Cohort VI.  

## Background
With the on going pandemic and almost everyone making use of online transactions, the credit card fraud has been increasing. This analysis conducted used a simulated or a dummy dataset that contains 25.5M transaction details and 25 variables (ssn, cc_num, first, last, gender, street, city, state, zip, lat, long, city_pop, job, dob, acct_num, trans_num, trans_date, trans_time, unix_time, category, amt, is_fraud, merchant, merch_lat, merch_long). This analysis was handled using Databricks Community Edition due to the size of the dataset.

## Objectives
Build a machine learning model that will detect fraud transactions

## Results
Logistic Regression and Decision trees are one of the top performing models in classifying fraud and non-fraud transactions
Credit card fraud is increasing in an alarming rate worldwide especially during the pandemic where people are mostly using cashless transactions
Machine Learning Algorithms are efficient in detecting credit card fraud but there's still more to develop to reduce false positive detection

## Recommendations
Model
- Check first with the credit card holder whether a transaction is fraud  before acting on it
- Run the model using Decision Tree classifier to confirm that it can output better accuracy
- Exploring and focusing on the Hyperparameter tuning and using different models is highly recommended given that the processing power is not an issue
- Use other features that can monitor monthly frequency of transactions per category

Features
- Providing additional features like family status, purchasing history and basic income can improve the models accuracy and prediction. (purchasing behavior)
- A more sophisticated feature engineering can be done in choosing which features are important in the modelling process
