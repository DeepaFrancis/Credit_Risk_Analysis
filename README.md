# Credit Risk Analysis

In this analysis we are applying machine learning to solve a real-world challenge: credit card risk.

## Resources
- Software: Python 3.7.6, VS code
- LoanStats_2019Q1.csv

## Results


### Naive Random Oversampling

<img width="650" alt="NaiveRandomOversampling(Picture1)" src="https://user-images.githubusercontent.com/89530570/151723374-8ffefa4e-651d-4c41-9a65-0c5c1287c19c.png">

- Accuracy Score of Naive Random Oversampling is 68.98%

### Smote Oversampling

![SmoteOversampling(Picture2)](https://user-images.githubusercontent.com/89530570/151723401-8ca2d52b-c39d-463b-ae12-22cc32215303.png)

- Accuracy Score of Smote Oversampling is 63.09%

### Undersampling

![undersampling(Picture3)](https://user-images.githubusercontent.com/89530570/151723445-374fb804-01c2-47fb-adc7-ba4b6e450ddb.png)

- Accuracy Score of Undersampling is 52.93%

### Combination (Over and Under) Sampling

![CombinationSampling(Picture4)](https://user-images.githubusercontent.com/89530570/151723486-21fe08a0-4b7b-49cb-969b-fec8ae1b488f.png)

- Accuracy Score of Combination (Over and Under) Sampling is 63.89%

### Balanced Random Forest Classifier

![BalancedRandomForest(Picture5)](https://user-images.githubusercontent.com/89530570/151723546-8bc4bcf4-8123-4db1-be0a-8eed03359507.png)

- Accuracy Score of Balanced Random Forest Classifier is 89.13%

### Easy Ensemble Adaboost Classifier

![EasyEnsembleAdaBoost(Picture6)](https://user-images.githubusercontent.com/89530570/151723586-6991aace-5588-4ef1-9fc2-dc8effa23110.png)

- Accuracy Score of Easy Ensemble Adaboost Classifier is 94.20%

## Summary

Among all these models, the Accuracy score of Easy Ensemble AdaBoost Classifier is highest. Using the Easy Ensemble AdaBoost Classifier will be the best.
