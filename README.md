# Credit_Risk_Analysis

## Machine Learning to Predict Credit Risk

In this analysis I have used six machine learning models on existing loan data in order to decide which model can best predict credit risk. Each model is trained with a portion of the existing data and then tested for accuracy using the remaining data. A summary of the results are included below for each model's balanced accuracy score, precision and recall.

## Test Results

### Model: Oversampling with RandomOverSampler
![RandomOverSampler](Resources/RandomOverSampler.png)
![RandomOverSampler2](Resources/RandomOverSampler2.png)

- The percentage of predictions that are correct for this model (balanced accuracy score) 


### Model: SMOTE Oversampling
![SMOTEoversampling](Resources/SMOTEoversampling.png)
![SMOTEoversampling2](Resources/SMOTEoversampling2.png)



### Model: Undersampling with Cluster Centroids
![ClusterCentroidsUndersampling](Resources/ClusterCentroidsUndersampling.png)
![ClusterCentroidsUndersampling2](Resources/ClusterCentroidsUndersampling2.png)



### Model: Combination (Over and Under) Sampling with SMOTEENN
![SMOTEENNoverunder](Resources/SMOTEENNoverunder.png)
![SMOTEENNoverunder2](Resources/SMOTEENNoverunder2.png)



### Model: Balanced RandomForest Classifier
![BRFC](Resources/BRFC.png)
![BRFC2](Resources/BRFC2.png)



### Model: Easy Ensemble AdaBoost Classifier
![EasyEnsambler](Resources/EasyEnsambler.png)
![EasyEnsambler2](Resources/EasyEnsambler2.png)