# Predicting Telecom Customer Churn
 Predicting Customer Churn from customer's various attributes
 
 ## Steps : 
 
 ###  1- Dataset is imbalanced which can be verified by value_counts 
 ###  2- Dropping nan values by  isnull()
 ###  3- Dropping customer_id should not affect the prediction
 ###  4- TotalCharges seems int but it is marked as object, checked for spaces present in the column
 ###  5- pd.to_numeric will change it into numeric data type
 ###  6- Feature engineering
 ###  7- Separate label from the features
 ###  8- Separate numerical and object features
 ###  9- Standard scaling on numerical attribute(mean =0 and std = 1)
 ###  10- One hot encoding for non numerical attribute
 ###  11- Imbalanced dataset so using SMOTE(Synthetic minority oversampling technique)
 ###  12- Using different models : SGDClassifier,Random Forest,applying grid search to select best feature
 ###  13- calculating feature importance 
 ###  14 - Using ensemble technique 
 ###  15 - Applying Boosting techniques
 
 
 ## f1 score : Accuracy achieved (f1 score): 78.21%(test set) and 81.443%(train set)
