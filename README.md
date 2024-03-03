# credit-risk-classification
## Overview of the Analysis
### Purpose of the analysis
The purpose of this anaylsis was to build and train a model to determine if a loan will be risky or not. This was done to help determine which loans should or should not be made in the futre.
### Financial information that the data was on and what needed to be predicted
The data used was on peer-to-peer lending and from a peer-to-peer lending company. The goal was to predict how credit worthy a barrower is. The prediction was made using the features loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt.
### Info about variable that I was trying to predict
The variable that was being predicted is loan status. This variable is a binary variable coded as 0 if the loan is healthy, and 1 if the loan is at a high risk of default.
### Stages of the machine learning process and methods used
Two machine learning models were used 

## Results
### Machine learning model using logistic regression
* Accuracy
* Precision
* Recall 

### Machine learning model using logistic regression and oversampling



This said the model should be improved given that the precision of predicting high risk loans is only 0.87 meaning the model is missing a lot of loans that are high risk. The underlying issue as to why the model is doing a poorer job of predicting high-risk loans seems to be a result of loan status being unbalanced, the target values are 75,036 healthy loans, but only 2,500 high-risk loans.
