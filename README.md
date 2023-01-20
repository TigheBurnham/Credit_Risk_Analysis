# Credit_Risk_Analysis

## Overview of the Analysis

In this module we learned that machine learning utilizes statistical algorithms to learn from data patterns and to make predictions. The main focus of the module delved into supervised machine learning. For our challenge we were tasked with looking at credit risk. It was stated that credit risk is an unbalanced classification problem because there are usually more good loans than there are risky loans. Therefore, this challenge required us to utilze different techniques to evaluate models with unbalanced classes. The models that were used for this task were the imbalanced-learn and scikit-learn libraries.

The data in this challenge was from the credit card dataset at LendingClub. LendingClub is a peer-to-peer lending services company. After loading in the data we were tasked to use RandomOverSampler, SMOTE, and ClusterCentroids algorithms to over and under sample the data. Next we used BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk. 

There were three technical analysis deliverables:

- Deliverable 1: Use Resampling Models to Predict Credit Risk.
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk.
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk.

## Results

- RandomOverSampler model

![Oversample](https://user-images.githubusercontent.com/112028534/213634505-2e4e882c-db07-40da-aa9e-497e0beada16.PNG)

The Balance Score is 63%.
The high risk precision score is 1% with a recall of 65%; therefore, the F1 score is 2%.
The low risk precision was 100% with a recall of 61%.

- SMOTE model

![Smote Over](https://user-images.githubusercontent.com/112028534/213634526-30895ede-d77b-4d91-9cf7-b4b1d0608013.PNG)

The Balance Score is 66%.
The high risk precision score is 1% with a recall of 63%; therefore, the F1 score is 2%.
The low risk precision score was 100% with a recall of 69%.

- ClusterCentroids model

![Cluster](https://user-images.githubusercontent.com/112028534/213634477-cdb0b295-89c6-4593-8053-535b9693556b.PNG)

The Balance Score is 66%
The high risk precision score is 1% with a recall of 69%; therefore, the F1 score is 1%.
The low risk precision score was 100% with a recall of 40%.

- SMOTEENN model

![Smoteenn](https://user-images.githubusercontent.com/112028534/213634546-cc01a682-b3dd-4809-94aa-12437a0e29e7.PNG)

The Balance Score is 54%
The high risk precision score is 1% with a recall of 72%; therefore, the F1 score is 2%.
The low risk precision score was 100% with a recall of 57%.

- BalancedRandomForestClassifier model

![RF](https://user-images.githubusercontent.com/112028534/213634589-6e059360-49c1-4100-a97f-7e50aa7bda6c.PNG)

The Balance Score is 79%
The high risk precision score is 3% with a recall of 70%; therefore, the F1 score is 6%
The low risk precision score was 100% with a recall of 87%.

- EasyEnsembleClassifier model

![EE](https://user-images.githubusercontent.com/112028534/213634611-15e25e9f-d317-4d4f-ace9-35d7bedeef74.PNG)

The Balance Score is 93%
The high risk precision score is 9% with a recall of 92%; therefore, the F1 score is 17%.
The low risk precision score was 100% with a recall of 95%.

## Summary


