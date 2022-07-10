# Credit_Risk_Analysis

## Machine Learning to Predict Credit Risk

In this analysis I have used six machine learning models on existing loan data in order to decide which model can best predict credit risk. Each model is trained with a portion of the existing data and then tested for accuracy using the remaining data. A summary of the results are included below for each model's balanced accuracy score, precision and recall.

## Test Results

### Model: Oversampling with RandomOverSampler
![RandomOverSampler](RandomOverSampler.png)
![RandomOverSampler2](RandomOverSampler2.png)

- The percentage of predictions that are correct for this model (balanced accuracy score) 


### Model: SMOTE Oversampling
![SMOTEoversampling](SMOTEoversampling.png)
![SMOTEoversampling2](SMOTEoversampling2.png)



### Model: Undersampling with Cluster Centroids
![ClusterCentroidsUndersampling](ClusterCentroidsUndersampling.png)
![ClusterCentroidsUndersampling2](ClusterCentroidsUndersampling2.png)



### Model: Combination (Over and Under) Sampling with SMOTEENN
![SMOTEENNoverunder](SMOTEENNoverunder.png)
![SMOTEENNoverunder2](SMOTEENNoverunder2.png)



### Model: Balanced RandomForest Classifier
![BRFC](BRFC.png)
![BRFC2](BRFC2.png)



### Model: Easy Ensemble AdaBoost Classifier
![EasyEnsambler](EasyEnsambler.png)
![EasyEnsambler2](EasyEnsambler2.png)