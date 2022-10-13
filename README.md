# Credit_Risk_Analysis

## Overview:

The purpose of this analysis was to use various machine learning models performance to determine the best model to predict credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes.
evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results:

### Naïve Random Oversampling

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/NRS1.PNG)

  -	Balanced Accuracy Score: 0.64

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/NRS2.PNG)

  - Precision: High risk – 0.01
  - Precision: Low risk – 1.00
  - Recall: High risk - 0.62
  - Recall: Low risk - 0.65


### SMOTE Oversampling

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/SMOTE1.PNG) 

- Balanced Accuracy Score: 0.63

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/SMOTE2.PNG) 
	
- Precision: High risk – 0.01
- Precision: Low risk – 1.00
- Recall: High risk - 0.62
- Recall: Low risk - 0.64


### Undersampling

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/Over1.PNG)  

- Balanced Accuracy Score: 0.51

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/over2.PNG) 

- Precision: High risk – 0.01
- Precision: Low risk – 1.00
- Recall: High risk - 0.59
- Recall: Low risk - 0.43


### Combination (Over and Under) Sampling

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/overandunder1.PNG)

- Balanced Accuracy Score: 0.65

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/overandunder2.PNG) 

- Precision: High risk – 0.01
- Precision: Low risk – 1.00
- Recall: High risk - 0.71
- Recall: Low risk – 0.59


### Balanced Random Forest Classifier

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/RFM1.PNG)
  
- Balanced Accuracy Score: 0.79

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/RFM2.PNG) 

- Precision: High risk – 0.03
- Precision: Low risk – 1.00
- Recall: High risk - 0.70
- Recall: Low risk – 0.87


### Easy Ensemble AdaBoost Classifer

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/Easy1.PNG)

- Balanced Accuracy Score: 0.93

![Alt Text](https://github.com/lauren1478/Credit_Risk_Analysis/blob/main/PNGs/Easy2.PNG) 

- Precision: High risk – 0.09
- Precision: Low risk – 1.00
- Recall: High risk - 0.92
- Recall: Low risk – 0.94


## Summary:
I recommend using the Balanced Random Forest Classifer model or the Easy Ensenble AdaBoost Classifier model as they produced the highest accuracy scores.

