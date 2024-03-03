# credit-risk-classification
## Overview of the Analysis
### Purpose of the analysis
The purpose of this anaylsis was to build and train a model to determine if a loan will be risky or not. This was done to help determine which loans should or should not be made in the futre.
### Financial information that the data was on and what needed to be predicted
The data used was on peer-to-peer lending and from a peer-to-peer lending company. The goal was to predict how credit worthy a barrower is. The prediction was made using the features loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt.
### Info about variable that I was trying to predict
The variable that was being predicted is loan status. This variable is a binary variable coded as 0 if the loan is healthy, and 1 if the loan is at a high risk of default. 75036 loans were classified as healthy, while 2500 were classified as high risk.
### Stages of the machine learning process and methods used
Two machine learning models were used, one using logistic regression and another using logistics regression with over sampling of the labels. Oversampling was used in the second model becuase of the inbalance in healthy versus high risk loans. The stages of the machine learning process for each of the models was the same, except for the use of oversampling in the second model. First the lables (loan status) was separtated from the data, and then the features (loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt) were separted and scaled using StandardScaler. StandardScaler was used becuase of the large differnces in some of the scales of the features. The module train_test_split from sklearn was then used to split the data into training and testing data. The logistic model was then instantiated and the model was fit using the training data. From this model predictions were then made and compared to the test data. Each of the models' performance were then examined using an accuracy score, confusion matrix and classification report.
## Results of accuracy, precision and recall scores
### Machine learning model using logistic regression
* Accuracy: 
* Precision
* Recall Scores
### Machine learning model using logistic regression and oversampling
* Accuracy
* Precision
* Recall Scores

## Summary of the results comparing the two models and recommendation
This said the model should be improved given that the precision of predicting high risk loans is only 0.87 meaning the model is missing a lot of loans that are high risk. The underlying issue as to why the model is doing a poorer job of predicting high-risk loans seems to be a result of loan status being unbalanced, the target values are 75,036 healthy loans, but only 2,500 high-risk loans.
