# Credit_Risk_Analysis

##Overview
The purpose for this analysis to analyse the information provided in the LoanStats_2019Q1.csv file and use it to predict credit risk for a potential clients. In this project, imbalance_learn and scikit-learn libraries to build models and test and predict. 

# Results
## Naive Random Oversampling results

The balanced accuracy score is 65%
![image](https://user-images.githubusercontent.com/107962343/202912908-6c04dbdc-429a-467b-9c3a-60bfad7ddf04.png)
![image](https://user-images.githubusercontent.com/107962343/202912939-a9745c09-6a9c-4e8c-b6eb-a36a2c91e27f.png)

## SMOTE Oversampling

Here, you can see the accuracy score is 66.2%
![image](https://user-images.githubusercontent.com/107962343/202913030-dadbddee-f4e7-4cb1-91da-930819f63cbe.png)

## Undersampling

Balanced accuracy score is again 66.2%
![image](https://user-images.githubusercontent.com/107962343/202913165-aff0d30f-1726-4893-88ce-8cdf9faf1556.png)

## Combination Undersampling and Oversampling

Here, the balanced accuracy score is 54.4% and the precision is 99%
![image](https://user-images.githubusercontent.com/107962343/202913252-d18de011-36cb-4793-8fc7-cc4c60970a54.png)

## Balanced Random Forest Classifier

Balanced accuracy score is 77.3%
![image](https://user-images.githubusercontent.com/107962343/202913389-1e733ebc-a13c-45c0-a3a3-69a93014860e.png)

## Easy Ensemble AdaBoost Classifier

Balanced accuracy score is 93.1%
![image](https://user-images.githubusercontent.com/107962343/202913481-f33a45e2-ad05-40ca-9e45-0bf4e859cfbb.png)

# Summary

Out of all the models used, it appears that the Easy Ensemble AdaBoost Classifier model had the best results at predicting which loans are high or low risk, with a very high accuracy score and a really good balance of precision and recall scores. 
