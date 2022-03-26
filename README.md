# Credit_Risk_Analysis
Module 17 Repo

## Overview of the analysis: 
The purpose of this analysis is to use machine learning to help predict credit risk based on previous loans.

## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.


### [Random Oversampling](https://github.com/mododds/Credit_Risk_Analysis/blob/main/RandomOversample.png)

Balance accuracy score: 50.6%

Precision score: 1%

recall score: 57%

- Random oversampling had okay recall scores, but very lower precision scores as a number of false positives were recorded.

### [Cluster Centroids Undersampling](https://github.com/mododds/Credit_Risk_Analysis/blob/main/ClusterCentroids.png)

Balance accuracy score: 65.2%

Precision score: 1%

recall score: 57%

- Random oversampling had okay recall scores, but very lower precision scores as a number of false positives were recorded.

### [SMOTE Oversampling](https://github.com/mododds/Credit_Risk_Analysis/blob/main/SMOTE.png)

Balance accuracy score: 65.2%

Precision score: 1%

recall score: 66%

- SMOTE oversampling had slightly better recall scores & accuracy scores, However, very low precision were recorded.

### [Combination Sampling (SMOTEEEN)](https://github.com/mododds/Credit_Risk_Analysis/blob/main/SMOTEEEN.png)

Balance accuracy score: 51.1%

Precision score: 1%

recall score: 70%

- Combination Sampling yielded lower accuracy scores, but slightly better recall scores. Still very low precision were recorded.

### [Balanced Random Forest Classifier](https://github.com/mododds/Credit_Risk_Analysis/blob/main/RandomForest.png)

Balance accuracy score: 78.7%

Precision score: 3%

recall score: 68%

- The balanced Random Forest model yielded better accuracy scores, but still very low precision scores

### [AdaBoost Classifier](https://github.com/mododds/Credit_Risk_Analysis/blob/main/AdaBoost.png)

Balance accuracy score: 50.5%

Precision score: 1%

Recall score: 76%

- This model had the best recall score, but still very poor precision and accuracy scores. 

## Summary: 

Based on the results above, there are too many false positives to recommend using any of the above model. 
I recommend you hire a professional to build a proper machine learning model, this way, you could ensure that the data input into the model was used most effectively.
