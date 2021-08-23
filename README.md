Week 11 Homework Submission
by Steve Stark

This assignment can be found in two notebooks within the same file as this README: credit_risk_resampling and credit_risk_ensemble. 

The objective was to predict credit risk via machine learning tools.

In credit_risk_resampling, data was imported, scaled with the StandardScaler from sklearn, and subjected to several tools for analysis: Logistic Regression, Naive Random Oversampling, SMOTE Oversampling, Undersampling, and Combination Sampling. 

Results were as folows: 
1. SMOTE Oversampling had the best balanced accuracy score.
2. All models had recall scores in the 99th percentile.
3. Naive Random Oversampling, SMOTE, and Combination Sampling all had geometric means of 0.99.

In credit_risk_ensemble, data was imported, scaled with the StandardScaler from sklearn, and then two algorithms were applied to the data: the Balanced Random Forest Classifier and the Easy Ensemble Classifier.

Results were as follow:
1. The Easy Ensemble Classifier had the best balanced accuracy score.
2. The Easy Ensemble Classifier also had the best recall score, at 93%.
3. The Easy Ensemble Classifier had the best geometric mean score.
4. The top three features are: 1. total_rec_prncp; 2. total_rec_int; and 3. total_pymnt.
