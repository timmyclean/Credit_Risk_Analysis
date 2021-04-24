# Credit_Risk_Analysis

## Overview
* "Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk." -- as per Canvas

## Results

### Naive Random Oversampling
  * Balanced Accuracy Score 0.6347321432168598
  * Imbalanced Classification Report
  ![image](https://user-images.githubusercontent.com/76462602/115965998-96dfe680-a4f9-11eb-9df0-f61cb65a0418.png)
### SMOTE Oversampling
  * Balanced Accuracy Score 0.6473010865755344
  * Imbalanced Classification Report
  ![image](https://user-images.githubusercontent.com/76462602/115966208-98f67500-a4fa-11eb-8d73-330613e7cceb.png)
### Undersampling
  * Balanced Accuracy Score 0.6473010865755344
  * Imbalanced Classification Report 
  ![image](https://user-images.githubusercontent.com/76462602/115966291-df4bd400-a4fa-11eb-9f3d-8c43f7c2415f.png)
### Combination (Over and Under) Sampling SMOTEEN
  * Balanced Accuracy Score 0.5293318990697431
  * Imbalanced Classification Report 
  ![image](https://user-images.githubusercontent.com/76462602/115966352-381b6c80-a4fb-11eb-9da3-5b2332cbbbfa.png)
### Balanced Random Forest Classifier
  * Balanced Accuracy Score 0.7877672625306695
  * Imbalanced Classification Report 
  ![image](https://user-images.githubusercontent.com/76462602/115966436-86c90680-a4fb-11eb-93fe-fd47213f4a44.png)
### Easy Ensemble AdaBoost Classifier
  * Balanced Accuracy Score 0.925427358175101
  * Imbalanced Classification Report 
  ![image](https://user-images.githubusercontent.com/76462602/115966492-c42d9400-a4fb-11eb-82f4-9ba6eea3017d.png)
  
## Summary
### Oversampling
 * Looking at the results for Naive Random and SMOTE and based on class materials the models are not effective in the prediction of bad loans. This is due to the precision score of 0.01 and Recall of 0.59. While SMOTE offered similar results of a precision score of 0.01 and Recall of 0.67. Along with this both with low accuracy scores.
### Undersampling
* Did not produce desired results as well as seen with scores

