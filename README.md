# Credit_Risk_Analysis


## Overview

We are analyzing credit risk which  is an inherently unbalanced classification problem. Using the imbalanced-learn and scikit-learn libraries we will build and evaluate models of our data using resampling. These techniques hopefully will determine which model can be used for reliably predicting credit risk. The data used is from the credit card credit dataset at LendingClub, a peer-to-peer lending services company. 


## Results


### Naive oversampling

- Accuracy Score and Confusion Matrix

![image](https://user-images.githubusercontent.com/68198233/163675457-9856737d-4466-4f0d-91c6-06452de21065.png)


- imbalanced classification report

![image](https://user-images.githubusercontent.com/68198233/163675478-6ff44d19-620e-4be2-b330-0098446144c7.png)



### SMOTE oversampling

- Accuracy Score and Confusion Matrix
![image](https://user-images.githubusercontent.com/68198233/163675548-394e8b4f-eb69-41ee-98a6-d4666bcba545.png)


- imbalanced classification report

![image](https://user-images.githubusercontent.com/68198233/163675609-b9070617-99c5-40f7-ad8d-a421655f6cfd.png)



### Undersampling

- Accuracy Score

![image](https://user-images.githubusercontent.com/68198233/163675649-cfa08fea-18c3-44ec-a84d-115f122cc911.png)

- Confusion Matrix

![image](https://user-images.githubusercontent.com/68198233/163675671-cadb7605-8ecb-4e31-a682-b893e7f5814f.png)


- imbalanced classification report

![image](https://user-images.githubusercontent.com/68198233/163675712-f24650bd-672d-47af-8ff9-24beefb61e29.png)



### Combination Over and Under Sampling

- Accuracy Score

![image](https://user-images.githubusercontent.com/68198233/163675864-941e5a23-d56c-4fde-a7ca-df17999847dc.png)


- Confusion Matrix

![image](https://user-images.githubusercontent.com/68198233/163675885-a8e67f78-b33f-473c-b4b2-393f0f4af2d6.png)


- imbalanced classification report

![image](https://user-images.githubusercontent.com/68198233/163675904-d4ff5a67-95ce-42fe-9ee9-c2d5461ad02d.png)


##Balanced Randem Forest Classifier

- Accuracy Score

![image](https://user-images.githubusercontent.com/68198233/163675974-06bcc875-a536-4c79-a2e1-f054efc4f8e5.png)


- Confusion Matrix

![image](https://user-images.githubusercontent.com/68198233/163675984-afd5d1fc-a962-481a-ae49-f8d71845721c.png)


- imbalanced classification report

![image](https://user-images.githubusercontent.com/68198233/163675998-3aded80e-8a21-4605-9568-2feab120f5d3.png)


### Easy Ensemble AdaBooster Classifier

Accuracy Score

![image](https://user-images.githubusercontent.com/68198233/163676064-e2ae99b2-1e1c-471b-8069-ca0d1252e341.png)


Confusion matrix

![image](https://user-images.githubusercontent.com/68198233/163676087-666cd8ff-8430-422d-bbf8-028dfc679158.png)


imbalanced classification report

![image](https://user-images.githubusercontent.com/68198233/163676100-1cc24c8f-c6ca-47e9-8756-4af34f3d8f1a.png)

##Summary

Based off of our accuracy score the easy ensemble adabooster classifier had the best results. With that said all of the models had a f1 score close to zero for high risk loans, which is certainly concerning. 


