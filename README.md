# Classification Homework
## In this assignment, I built and evaluated different machine-learning models to predict credit risk using data from LendingClub. I used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the resampling and ensamble techniques. 

 In the first workbook (credit_risk_resampling), I used the imbalanced learn library to resample the LendingClub data and answer the following questions: 
> Which model had the best balanced accuracy score?
>> Of these four models, the SMOTE Oversampling and the ClusterCentroids Undersampling models had the best balanced accuracy score of 0.6514992150524688. 

> Which model had the best recall score?
>> Of these four models, the SMOTE Oversampling model had the best recall score of 0.69. 

> Which model had the best geometric mean score?
>> Of these four models, the SMOTE Oversampling model had the best geometric mean score of 0.65. 

In the second workbook, I trained and compared two different ensemble classifiers to predict loan risk and evaluate each model, using the Balanced Random Forest Classifier and the Easy Ensemble Classifier.
> Which model had the best balanced accuracy score?
>> Of these two models, the Easy Ensemble Classifier model had the best balanced accuracy score of 0.9293497315796027. 

> Which model had the best recall score?
>> Of these two models, the Balanced Random Forest Classifier model had the best recall score of 0.25.

>Which model had the best geometric mean score?
>>Of these two models, the Balanced Random Forest Classifier model had the best geometric mean score of 0.44.

>What are the top three features?
>>The top three features that impact the riskiness of a loan are the total received principal, the total payment invested, and the received interest. 

