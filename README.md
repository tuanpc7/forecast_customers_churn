# Forcast Customers Churn from Credit Cards Users Data
 
## Objective

This file provides the credit card information and based on this data, we will try to forecast the customer who can higher chance to close account.

## Data Source. 

The data*set was downloaded from Kaggle. https://www.kaggle.com/c/1056lab-credit-card-customer-churn-prediction

## Data Description

  + **Client_ID**: Client ID
  + **Customer_Age**: Customer's age in years
  + **Gender**: F=Female, M=Male
  + **Dependent_count**: Number of dependent families
  + **Education_Level**: Uneducated, High Schoool, College, Graduate, Post-Graduate, Unknown
  + **Marital_Status**: Married, Single, Divorced, Unknown
  + **Income_Category**: Less than $40K, $40K - $60K, $60K - $80K, $80K - $120K, $120K +, Unknown
  + **Card_Category**: Blue, Silver, Gold, Platinum
  + **Months_on_book**: Months on book
  + **Total_Relationship_Count**: Total number of products held by the customer
  + **Months_Inactive_12_mon**: Number of months inactive in the last 12 months
  + **Contacts_Count_12_mon**: Number of contacts in the last 12 months
  + **Credit_Limit**: Credit limit on the credit card
  + **Total_Revolving_Bal**: Total revolving balance on the credit card
  + **Avg_Open_To_Buy**: Average Open-To-Buy credit line in the last 12 months
  + **Total_Amt_Chng_Q4_Q1**: Change in transaction amount (Q4 over Q1)
  + **Total_Trans_Amt**: Total transaction amount in the last 12 months
  + **Total_Trans_Ct**: Total Transaction count
  + **Total_Ct_Chng_Q4_Q1**: Change in transaction count (Q4 over Q1)
  + **Avg_Utilization_Ratio**: Average ratio of credit card balances to credit card limit.
  + **Attrition**: 1=Closed, 0=Not closed


## Code Structure

This project is done in R-programming, which is documented in R-markdown file called BankChurners.Rmd.

Data is stored in `data/BankChurners.csv`


## Evaluation Metric

The evaluation metric for this project is AUC (Area Under the Curve) ROC (Receiver Operating Characteristics) curve.


## Model Selections

Three models used are GLM, SVM and Decision Tree


