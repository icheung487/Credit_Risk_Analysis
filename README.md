# Credit_Risk_Analysis

#Overview of the analysis: 
Fast Lending wants to use machine learning to predict credit risk.  We will build different machine learning models to predict credit risk.  The purpose is to train and evaluate different models to see which model would be best to predict credit risk

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

# Native Resampling Model:
![image](https://github.com/icheung487/Credit_Risk_Analysis/blob/main/images/Native_Random_oversampling.png)


* Balance accuracy score = 65%
* Precision scores = high-risk 0.01 / low-risk 1.00
* Recall scores = high-risk 0.62 / low-risk 0.68
* Avg/Total 99% for precision / 68% for recall 

# Smote Oversampling Model:
![image](https://github.com/icheung487/Credit_Risk_Analysis/blob/main/images/Smote_undersampling.png)

* Balance accuracy score = 64%
* Precision scores = high-risk 0.01 / low-risk 1.00
* Recall scores = high-risk 0.63 / low-risk 0.66
* Avg/Total 99% for precision / 66% for recall 

# Undersampling Model:

![image](https://github.com/icheung487/Credit_Risk_Analysis/blob/main/images/Undersampling.png)

* Balance accuracy score = 64%
* Precision scores = high-risk 0.01 / low-risk 1.00
* Recall scores = high-risk 0.61 / low-risk 0.45
* Avg/Total 99% for precision / 45% for recall 

# Combination Sampling Model:
![image](https://github.com/icheung487/Credit_Risk_Analysis/blob/main/images/Combination_Sampling.png)

* Balance accuracy score = 64%
* Precision scores = high-risk 0.01 / low-risk 1.00
* Recall scores = high-risk 0.61 / low-risk 0.45
* Avg/Total 99% for precision / 45% for recall 

# Balanced Random Forest Model:
![image](https://github.com/icheung487/Credit_Risk_Analysis/blob/main/images/Balanced_random_forest_classifier.png)

* Balance accuracy score = 81%
* Precision scores = high-risk 0.04 / low-risk 1.00
* Recall scores = high-risk 0.72 / low-risk 0.90
* Avg/Total 99% for precision / 90% for recall 

# Easy Ensemble Classifier Model:
![image](https://github.com/icheung487/Credit_Risk_Analysis/blob/main/images/Ensemble_Classifier.png)

* Balance accuracy score = 92%
* Precision scores = high-risk 0.07 / low-risk 1.00
* Recall scores = high-risk 0.91 / low-risk 0.94
* Avg/Total 99% for precision / 94% for recall 


Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

We used different techniquest to deal with class imbalance.  In the first deliverable we used over and undersampling, then a combination approach to deal with unequal classification. 

In deliverable two, we used SMOTEENN approach to resample both over and undersampling data. Then in deliverable 3, we used boosting to combine weak sampling together. By using adaptive boosting, you can train and evaluate the errors to retrain the model. 

Overall, I would recommend the ensemble classifier model since it had the highest accuracy score of 92% and a high recall score. 

