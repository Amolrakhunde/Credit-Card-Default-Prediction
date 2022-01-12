# Credit-Card-Default-Prediction
## Problem Statement:

The main objective is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

## Data Features:-

This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following variables as explanatory variables:


* ID: Unique ID of each client
* LIMIT_BAL: Amount of the given credit (NT dollar).
* Gender: Gender of customer. (1 = male; 2 = female)
* Education: Education qualification of customers. (1 = graduate school; 2 = university; 3 = high school; 4 = others)
* Marital Status: Marital status of customer. (1 = married; 2 = single; 3 = others)
* Age: Age of customer in years.
* History of Past Payment: We tracked the past monthly payment records from April to September, 2005.
* PAY_1, PAY_2, PAY_3, PAY_4, PAY_5 and PAY_6 are repayment status in September, August, July, June, May and April 2005 respectively.
* Amount of Bill Statement:(NT dollar)
* BILL_AMT1, BILL_AMT2, BILL_AMT3, BILL_AMT4, BILL_AMT5 and BILL_AMT6 are amount of bill statement in September, August, July, June, May and April 2005 respectively.
* Amount of Previous Payment: (NT dollar)
* PAY_AMT1, PAY_AMT2, PAY_AMT2, PAY_AMT2, PAY_AMT2 and PAY_AMT2 are amount of previous payment in September, August, July, June, May and April 2005 respectively
* Default Payment Next Month: Default payment (1=yes, 0=no)

## Steps Involved:-
* Data Cleaning
* Data Preprocessing
* EDA
* Handling Class Imbalance
* Transformation & Splitting of data
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine
* Gradient Boosting
* XG Boosting
* Cross Validation & Hyperparameter Tunning
* Comparison of Model
* Combined ROC Curve
* Feature Importance

## Conclusion:-

1. From all baseline model, Random Forest classifier shows highest test accuracy and F1 score and AUC.

2. Baseline model of Random Forest and decision tree shows huge difference in train and test accuracy which shows overfitting.

3. After cross validation and hyperparameter tunning, XG Boost shows highest test accuracy score of 87% and AUC is 0.874.

4. Cross validation and hyperparameter tunning certainly reduces chances of overfitting and also increases performance of model.

