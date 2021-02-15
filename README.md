# Credit_Risk_Analysis

Thanks to Jill I am usings a credid card dataset from LendingClub to oversample the data using
RandomOverSampler and SMOTE algorithms. I'll also undersample the data with the ClusterCentroids 
algorithm. With these methods I use the SMOTEENN algorithm to combine both the over- and undersampling 
approaches. With the BalancedRandomForestClassifier and the EasyEnsembleClassifier machine learning 
models I'll reduce bias and predict credit risk. To help me clarify the output of these algorithms 
I've used this source for information on Precision, Recall and F1 Scores. 
[Source](https://towardsdatascience.com/accuracy-precision-recall-or-f1-331fb37c5cb9)


For all three algorithms, the following have been completed:
[Credit_Risk_Resampling](https://github.com/Mattiejordan/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb)


![images/1.NaiveOversampling0.64807](images/1.NaiveOversampling0.64807.PNG)
* Naive OverSampling has an accuracy of 0.64807

![images/2.smoteOversampling0.66257](images/2.smoteOversampling0.66257.PNG)
* Smote OverSampling has an accuracy of 0.66257

![images/3.undersampling0.648628](images/3.undersampling0.648628.PNG)
* UnderSampling has an accuracy of 0.64862

The combinatorial SMOTEENN algorithm does the following:
[Credit_Risk_Ensemble](https://github.com/Mattiejordan/Credit_Risk_Analysis/blob/main/credit_risk_ensemble.ipynb)


![images/4.smoteennoverunder0.648629](images/4.smoteennoverunder0.648629.PNG)
* Smote Over- and UnderSampling has an accuracy of 0.64862

![images/5.balancedrandomforest0.87352513](images/5.balancedrandomforest0.87352513.PNG)
* Balanced Random Forest Classifier has an accuracy of 0.87352

![images/6.easyensembleadaboost0.873525](images/6.easyensembleadaboost0.873525.PNG)
* Easy Ensemble AdaBoost Classifier has an accuracy of 0.87352


Summary: Summarize the results of the machine learning models, and include 
a recommendation on the model to use, if any. If you do not recommend any 
of the models, justify your reasoning.
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there 
is no recommendation with a justification (3 pt)




Deliverable 1: Use Resampling Models to Predict Credit Risk
![images/1.Resampling](images/1.Resampling.PNG)

Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
![images/2.smoteenn](images/2.smoteenn.PNG)


The BalancedRandomForestClassifier algorithm does the following:
Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
![images/3.easye](images/3.easye.PNG)
Balanced Random Forest Classifier

The EasyEnsembleClassifier algorithm does the following:
![images/3.easyad](images/3.easyad.PNG)
Easy Ensemble AdaBoost Classifier