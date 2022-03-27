# Supervised Machine Learning - Predicting Credit Risk  
Building a machine learning model that will attemt to predict whether a loan from LendingClub will become high risk or not.  
## Retrieve Data  
Using 2019 data to predict the credit risk of loans from the first quarter of 2020.  
** Note: The data is undersampled to give a even number of high and low risk loans. For the original dataset, only 2.2% of the loans were categorized as high risk. To get an accurate model, special techniques need to be used on imbalanced data. Undersampling is one of the techniques, oversampling and SMOTE are other techniques used.  
  
## Preprocessing: Converting Categorical Data to Numberic 
  
Create a training set from the 2019 loans to convert the categorical data to numeric columns. Create a testing set from the 2020 loans.  
  
## Consider the Models  
  
Creating and compare two models on this data: a logistic regression, and a random forests classifiers.  
  
## Fit a LogisticRegression Model and RandomForestClassifier Model  
  
Create a LogisticRegression model, fit it to the data, and print the model's score. Do the same for a RandomForestClassifier.  
  
## Revisit the Preprocessing: Scale the Data  
  
The data going into these models was never scaled, an important step in preprocessing. Scale the training and testing sets. Fit and score the LogisticRegression and RandomForestClassifier models on the scaled data.  
  
### References  
  
LendingClub (2019-2020) _Loan Stats_. Retrieved from: [https://resources.lendingclub.com/](https://resources.lendingclub.com/)
