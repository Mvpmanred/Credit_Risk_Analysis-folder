# Credit_Risk_Analysis-folder

## Overview
The purpose of this analysis is using my knowledge of the supervised machine learning models, I will evaluate these machine learning models by using resampling to determine which is better at predicting credit risk. First, I will use the oversampling RandomOverSampler and SMOTE algorithms, and then I will use the undersampling ClusterCentroids algorithm. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

## Results

Below are the results from all machine learning models to predict for high risk loans. 


1.Navie Random Overshampling
![Capture1 Naive Random Overshampling](https://user-images.githubusercontent.com/92561493/155933713-5dcd5a5e-f12b-486c-b9f7-0a702289e9f5.PNG)
- Accuracy score: 67.14%
- Precision: 99%
- Sensitivity: 70%




2. SMOTE Oversampling
![SMOTE Oversampling](https://user-images.githubusercontent.com/92561493/155934192-0f40004d-163a-4ed3-9d83-8c7817e11680.PNG)
- Accuracy score: 65.86%
- Precision: 99%
- Sensitivity: 68%



3. Cluster Centroids
![Cluster Centroids algorithmn](https://user-images.githubusercontent.com/92561493/155936371-050f3a39-9a5d-400a-8a0a-00abdc7836f5.PNG)
- Accuracy scrore: 64.8%
- Precision: 99%
- Sensitivity: 68%




4. SMOTEENN algorithm
![SMOTEENN algorithm](https://user-images.githubusercontent.com/92561493/155937095-051193e7-24d3-4d92-8b1f-9ab8ec5a07d8.PNG)
- Accuracy score: 66.65%
- Precision: 99%
- Sensitivity: 60%



5. Balanced Random Forest Classifier
![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/92561493/155937415-99f08828-1731-4faa-a94a-998a4f93bcd3.PNG)
- Accuracy score: 77.70%
- Precision: 99%
- Sensitivity: 88%



6.Easy Ensemble AdaBoost Classifier
![easy ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/92561493/155937528-bcf0401b-8914-4c81-b6aa-7b690beb4226.PNG)
- Accuracy score: 93.21%
- Precision: 99%
- Sensitivity: 94%



## Summary
As we can see the results from all machine learning models above, Easy ensemble Classifier model has 93.21% accuracy score predicting the high risk loan status. It is the highest of all learning models. Moreover, it has 94% sensitivity. Sensitivity = True positive/(True positive + False Negative). It is also the hightest among all learning models. We recommend Easy Ensemble AdaBoost Classifier model to predict high risk loand status.

