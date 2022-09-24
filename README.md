# Credit_Risk_Analysis
Machine Based Learning and Credit Risk Analysis
Before even starting the analysis we must clean and read the data 

![image](https://user-images.githubusercontent.com/104408782/192101508-7b12920f-e38b-4052-bc15-50360c72b2d1.png)
Drop Null rows & convert some rows, look at the top few rows to be sure everything is lining up and the data was parsed correctly. 

![image](https://user-images.githubusercontent.com/104408782/192101580-8b3652d2-126d-4fc1-a94b-37e060598f42.png)

## Create a machine learning model to Predict Credit Risk
Method: Using several Machine Learning models, I'll analyze the LoanStats_2019Q1 dataset

The Classification report contains the Precision, Recall, f1-score, geo, iba, Support, 
Precision, or accuracy. F1-Score or Harmonic Mean = 2(Precision * Sensitivity)/(Precision + Sensitivity)
The tension between precision and sensitivity is important. High sensitive algorithyms are aggressive but risk more false positives. High Precision is more conservative so that predicted positives are true positives, but you may miss other positives. One must be mindful of balancing the two based on the scenerio. 
An imbalance will yield a low F1 score. 

### Resampling Model Predictions
OverSampling: 63% accuracy
![image](https://user-images.githubusercontent.com/104408782/192101695-92a3838f-2421-4410-ad72-ea0817edfa5c.png)

Smote OverSampling: 63% accuracy 
![image](https://user-images.githubusercontent.com/104408782/192101733-da3d31d0-0b19-4eca-b924-16bbf8f107f9.png)

UnderSampling: 52% accuraccy not so great
![image](https://user-images.githubusercontent.com/104408782/192101788-d3c0f3aa-a8d5-49f9-925d-3b3f20b884a4.png)


### SMOTEENN Algorithm Predictions
Combination, Over & Under, Sampling: 65% accuracy
![image](https://user-images.githubusercontent.com/104408782/192102487-48259671-236d-4517-b9a3-24d254ef42dd.png)

### Ensemble Classifiers to predict



## Results: 

## Summary
