# Credit_Risk_Analysis

## Machine Learning to Predict Credit Risk

In this analysis I have used six machine learning models on existing loan data in order to decide which model can best predict credit risk. Each model is trained with a portion of the existing data and then tested for accuracy using the remaining data. A summary of the results are included below for each model's balanced accuracy score, precision and recall.

## Test Results

### Model: Oversampling with RandomOverSampler
![RandomOverSampler](Resources/RandomOverSampler.png)
![RandomOverSampler2](Resources/RandomOverSampler2.png)

- The percentage of predictions that are correct for this model (balanced accuracy score) is 63.7%
- The precision score is 1.0% for high risk loans compared to 100.0% for low risk loans
- The recall score is 62.0% for high risk loans compared to 65.0% for low risk loans


### Model: SMOTE Oversampling
![SMOTEoversampling](Resources/SMOTEoversampling.png)
![SMOTEoversampling2](Resources/SMOTEoversampling2.png)

- The percentage of predictions that are correct for this model (balanced accuracy score) is 63.0%
- The precision score is 1.0% for high risk loans compared to 100.0% for low risk loans
- The recall score is 62.0% for high risk loans compared to 64.0% for low risk loans


### Model: Undersampling with Cluster Centroids
![ClusterCentroidsUndersampling](Resources/ClusterCentroidsUndersampling.png)
![ClusterCentroidsUndersampling2](Resources/ClusterCentroidsUndersampling2.png)

- The percentage of predictions that are correct for this model (balanced accuracy score) is 52.1%
- The precision score is 1.0% for high risk loans compared to 100.0% for low risk loans
- The recall score is 57.0% for high risk loans compared to 47.0% for low risk loans


### Model: Combination (Over and Under) Sampling with SMOTEENN
![SMOTEENNoverunder](Resources/SMOTEENNoverunder.png)
![SMOTEENNoverunder2](Resources/SMOTEENNoverunder2.png)

- The percentage of predictions that are correct for this model (balanced accuracy score) is 63.8%
- The precision score is 1.0% for high risk loans compared to 100.0% for low risk loans
- The recall score is 70.0% for high risk loans compared to 57.0% for low risk loans


### Model: Balanced RandomForest Classifier
![BRFC](Resources/BRFC.png)
![BRFC2](Resources/BRFC2.png)

- The percentage of predictions that are correct for this model (balanced accuracy score) is 78.8%
- The precision score is 4.0% for high risk loans compared to 100.0% for low risk loans
- The recall score is 67.0% for high risk loans compared to 91.0% for low risk loans

### Model: Easy Ensemble AdaBoost Classifier
![EasyEnsambler](Resources/EasyEnsambler.png)
![EasyEnsambler2](Resources/EasyEnsambler2.png)

- The percentage of predictions that are correct for this model (balanced accuracy score) is 92.5%
- The precision score is 7.0% for high risk loans compared to 100.0% for low risk loans
- The recall score is 91.0% for high risk loans compared to 94.0% for low risk loans


## Summary

Each one of these models has a very low precision score, indicating that none of them are reliable for predicting a high risk loan. The recall scores improvement with the Combination Sampling model, Balanced Random Forest model, and Easy Ensemble Classifier. With the exception of the Cluster Centroids model, the accuracy scores improved with each model. Easy Ensamble Classifier has the highes accuracy score at 92.5%. However, I do not beleive these are good enough numbers to justify relying on these models to make decisions on new loans coming in for the business. 


