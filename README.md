# Credit_Risk_Analysis

## Loan prediction risk analysis - Overview 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We can use different techniques to train and evaluate models with unbalanced classes. Multible libraries and algorithms were used to build and evaluate models using resampling:

imbalanced-learn
scikit-learn
RandomOverSampler
SMOTE algorithms
ClusterCentroids algorithm
SMOTEENN algorithm
BalancedRandomForestClassifier (bias reduction model)
EasyEnsembleClassifier (bias reduction model)

## Purpose

Define how a machine learning algorithms are used in data analytics.
Create training and test groups from data sets.
Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
Compare, advantages and disadvantages of supervised learning algorithm.
Show and determine which supervised learning algorithm is best used for a given data set or scenario.
Use ensemble and resampling techniques to improve performance of the sample model.

## Results

For the six machine learning models tested, including, respective balanced accuracy, precision, and recall scores are shown here:

Naive Random Oversampling

![204424096-939e936b-c7c0-4e20-8695-596548753f49](https://user-images.githubusercontent.com/109055148/213609885-f5d77e63-f299-4076-a339-661ed01b26cb.png)

Balanced Accuracy: 0.648767580808264
Precision: The precision is low for High-risk loans 0.01 and is high for Low-risk loans 1.00.
Recall: High/Low risk = .61/.69


## SMOTE Oversampling


![204425178-d739d560-7b6b-4bdf-b4d8-1fef902d388e](https://user-images.githubusercontent.com/109055148/213609945-3aba81e4-b8e4-4de0-b663-76e39fcc3ff1.png)


Balanced Accuracy: 0.6159507435206336 Precision: The precision is low for High-risk loans 0.01 and is high for Low-risk loans 1.00. Recall: High/Low risk = .59/.65


## Undersampling

![204425538-a26f14c4-da99-4fbd-9476-584b572af843](https://user-images.githubusercontent.com/109055148/213610001-2b22096c-8bc3-462e-ba05-8e22d322183b.png)

Balanced Accuracy: 0.6159507435206336
Precision: The precision is low for High-risk loans 0.01 and is high for Low-risk loans 1.00.
Recall: High/Low risk = .59/.46

## Combination Under-Over Sampling


![204425737-c466b9a7-d433-4f05-a962-33ea900d6758](https://user-images.githubusercontent.com/109055148/213610097-3d18ddbb-2709-4101-96bd-b64f7d0757ee.png)


Balanced Accuracy: 0.6419346846030192
Precision: The precision is low for High-risk loans 0.01 and is high for Low-risk loans 1.00.
Recall: High/Low risk = .70/.58

## Balanced Random Forest Classifier

![204426092-1a037c08-498f-4f1e-acc5-cfaec974844c](https://user-images.githubusercontent.com/109055148/213610165-9080d2f5-0183-4833-97d7-17e142431006.png)

Balanced Accuracy: 0.7877672625306695
Precision: The precision is low for High-risk loans 0.04 and is high for Low-risk loans 1.00.
Recall: High/Low risk = .67/.91

## Easy Ensemble AdaBoost Classifier


![204426324-e2f267de-af00-45cd-9bd9-eb16e708eb19 (1)](https://user-images.githubusercontent.com/109055148/213610251-aed99b39-288d-4317-81b3-974d1051fa80.png)

Balanced Accuracy: 0.925427358175101
Precision: The precision is low for High-risk loans and is high 0.07 for Low-risk loans 1.00.
Recall: High/Low risk = .91/.94

## Summary

Working with balanced accuracy, the highest compared accuracy is between 0 and 1 which is closest to 1, representing the best machine learning model for our analysis. Credit card data, the Easy Ensemble AdaBoost Classifier shows to be the best model to show this data, with a .93 balanced accuracy. Other models tested showed below .80 balanced accuracy.

Precision data across each model presented similar data, and showed to be within an appropriate data range. The recall score shows to also fall within 0 and 1, with the data showing to be closer to 1, determining to be the better model.

Finally, Easy Ensemble AdaBoost Classifier showed to have the highest recall score, making it the best machine learning model, which can be used for further credit card analysis.

