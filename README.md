# Credit_Risk_Analysis

## Overview
### The purpose of this analysis is to use supervised machine learning techniques to predict credit risk to provide a more efficient and reliable loan experience; it also will allow to identify good candidates for loans. All this by building several supervised machine learning models and algorithms using techniques such as resampling and boosting.

## Below, all six machine learning models' results are displayed.

### 1. Naive Random Oversampling
#### Balanced accuracy scores = 64.44%
![image](https://user-images.githubusercontent.com/88596274/151838848-808a4a79-bae0-4dde-bbe3-bb1c3bc862ef.png)


### 2. SMOTE Oversampling
#### Balanced accuracy scores = 66.25%
![image](https://user-images.githubusercontent.com/88596274/151839001-ec71ff27-e337-493d-b040-30eb391ec50d.png)


### 3. Undersampling 
#### Balanced accuracy scores = 54.42%
![image](https://user-images.githubusercontent.com/88596274/151839039-d231b48d-c804-4645-9bf2-7f1c6467a8bc.png)


### 4. Combination (Over and Under) Sampling
#### Balanced accuracy scores = 64.83%
![image](https://user-images.githubusercontent.com/88596274/151839079-d595a29f-311c-4067-9a0b-a65f1d787416.png)


### 5. Balanced Random Forest Classifier
#### Balanced accuracy scores = 76.97%
![image](https://user-images.githubusercontent.com/88596274/151839174-7630a9d7-3726-4191-9f08-eac0f9682fb3.png)
![image](https://user-images.githubusercontent.com/88596274/151839201-ec3d3b7b-8ae4-4db0-9eb2-4fb5f2cd507b.png)


### 6. Easy Ensemble AdaBoost Classifier
#### Balanced accuracy scores = 93.17%
![image](https://user-images.githubusercontent.com/88596274/151839232-da72c726-98c3-4a8f-a0e1-7966a27767b2.png)
![image](https://user-images.githubusercontent.com/88596274/151839249-7a4a4df7-28ed-4bda-8525-ec3f41793b66.png)


## Summary
### In this case, the results of the machine learning models have all demonstrated an acceptable level of precision, having the last two prospects, five (5) and six (6) with a superior precision over the rest. Moreover, these last two models, also possess a higuer accuracy score:
### 5. Balanced Random Forest Classifier with a 76.97%, and
### 6. Easy Ensemble AdaBoost Classifier with a 93.17%
### The recommendation for this specific dataset will be to use an Ensamble Learner model and train a Ease Ensamble Adaboost classifier due to its high level of precision an accuracy.
