# M.Sc. in Artificial Intelligence 
## Machine Learning Project

## Description
Purpose of this analysis is the prediction of customer churn for a Telecommunication company.  The dataset is from Kaggle and includes customers with some features and a flag if a specific customer has churned or not. 

In order to answer the above question we apply Supervised Machine learning algorithms and more specifically Decision Tree and Logistic Regression.   

## Data
The data include 7043 customers and features which are both categorical and continuous.  
Categorical features are:
gender
SeniorCitizen
Partner
Dependents
PhoneService
MultipleLines
InternetService
OnlineSecurity
OnlineBackup
DeviceProtection
TechSupport
StreamingTV
StreamingMovies
Contract
PaperlessBilling
PaymentMethod

Continuous featurse are:
tenure
MonthlyCharges
TotalCharges

## Data Pre-processing
In order to better understand the data we apply some descriptive analysis for the continuous variables along with some histograms/frequency tables for the categorial variables. 
Moreover, we need to recode the categorical variables to binaries with hot-encoding. 
Also, we split the data to train and test data set.  The train set is 85% of the original dataset. 

## Machine Learning algorithms
For the purpose of the analysis we have deployed a Decision tree and a logistic regression model.





