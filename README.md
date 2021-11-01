# Credit_Risk_Analysis

### Challenge Overview 
In this challenge it applies with machine learning models to predicting credit card risk. This is useful for determing whether someone is considered a good candidate for a possible loan that could benefit and lead them to lower rates. 


The machine learning models that were adopted were:
* Random Over Sampler 
* SMOTE Oversampling 
* Cluster Centroids Undersampling 
* SMOTEENN (Over and Under) Sampling 
* Easy Ensemble ADABoost Classifier 
* Balanced Random Forest Classifier

Deliverable 1: Use Resampling Models to Predict Credit Risk

Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

Deliverable 4: A Written Report on the Credit Risk Analysis 

### Resources 
* Data Source: LoanStats_2019Q1.csv
* Software: Python 3.7.9, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 

### Random Oversampling 

![Screenshot (249)](https://user-images.githubusercontent.com/64110317/139606870-aa5e24e2-393c-4f46-a5e7-c76c9ab7dee7.png)


![Screenshot (251)](https://user-images.githubusercontent.com/64110317/139607550-c5fc8a02-63a3-4edb-a208-194a35f0d186.png)



The results are pretty similar to the previous model.


The balanced accuracy score is 63%

The high_risk precision is about 1% only with 62% sensitivity which makes a F1 of 2% only.

Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 68%


### SMOTE Oversampling 

![Screenshot (253)](https://user-images.githubusercontent.com/64110317/139607464-97ffdca9-67c6-4544-a7fa-648c75e3266d.png)


![Screenshot (255)](https://user-images.githubusercontent.com/64110317/139607605-8c249b3a-da36-43d4-8d61-283f4e4d8cb7.png)



The results are pretty similar to the previous model.

The balanced accuracy score is 63%.

The high_risk precision is about 1% only with 64% sensitivity which makes a F1 of 2% only.

Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 64%.


### ClusterCentroids model 



![Screenshot (257)](https://user-images.githubusercontent.com/64110317/139608021-6a191897-846b-4462-88e6-e3b161748b27.png)


Here the balanced accuracy score is down to about 53%.

The high_risk precision is still 1% only with 61% sensitivity which makes a F1 of 1%.

Due to the high number of false positives, the low_risk sensitivity is only 45%.


### SMOTEENN model


![Screenshot (259)](https://user-images.githubusercontent.com/64110317/139608180-b554bdba-228f-40a7-8c8d-5eef60fbd0f7.png)




The balanced accuracy score is about 63%.

The high_risk precision is still 1% only with 64% sensitivity which makes a F1 of only 2%.

Due to the high number of false positives, the low_risk sensitivity is 62%.



### BalancedRandomForestClassifier model


![Screenshot (261)](https://user-images.githubusercontent.com/64110317/139608536-1ff81905-178d-45f9-850c-929487925243.png)


The balanced accuracy score improved to about 79%.

The high_risk precision is still low at 4% only with 70% sensitivity which makes a F1 of only 7%.

Due to a lower number of false positives, the low_risk sensitivity is now 87% with 100% presicion.


### EasyEnsembleClassifier model 


![Screenshot (263)](https://user-images.githubusercontent.com/64110317/139609037-9739bb73-3f27-43cb-91b0-c81c5cddde22.png)


### Summary


The models shown in this analysis show weak precisions in determining if a cresit is actually high. The Ensemble models were accurate on the sensitivity of high credit risks and the last model used had shown a recall
