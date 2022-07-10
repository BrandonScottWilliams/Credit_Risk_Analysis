# Credit_Risk_Analysis
## Overview of the analysis
The purpose of the analysis is to train and evaluate supervised learning models to help with predicting whether someone is a high or low credit risk. 
## Results
### Random Over Sampler
* Balanced accuracy score  0.595
* Low Risk Precision 1   
* Low Risk Recall 0.63
* High Risk Precision 0.01
* High Risk Recall 0.56


  ![image](https://user-images.githubusercontent.com/99148657/178123094-2a7d67bf-0ef9-47bb-ad4c-ee87565c880d.png)

### SMOTE
* Balanced accuracy score  0.636%
* Low Risk Precision 1
* Low Risk Recall 0.66
* High Risk Precision 0.01
* High Risk Recall 0.61


  ![image](https://user-images.githubusercontent.com/99148657/178123127-ec718d5a-b98e-4314-8206-20307cb3a61d.png)

### Cluster Centroids
* Balanced accuracy score  0.636%
* Low Risk Precision 1  
* Low Risk Recall 0.45
* High Risk Precision 0.00
* High Risk Recall 0.58

  ![image](https://user-images.githubusercontent.com/99148657/178123147-adcd5bc3-4248-4ea3-8186-0285ed665b02.png)

### SMOTEENN
* Balanced accuracy score  0.517%
* Low Risk Precision 1   
* Low Risk Recall 0.57
* High Risk Precision 0.01
* High Risk Recall 0.75

  ![image](https://user-images.githubusercontent.com/99148657/178123160-4c48b3b4-d499-41e4-b42b-711d62e1ffee.png)

### BalancedRandomForestClassifier
* Balanced accuracy score  0.788%
* Low Risk Precision 1  
* Low Risk Recall 0.91
* High Risk Precision 0.04
* High Risk Recall 0.67

  ![image](https://user-images.githubusercontent.com/99148657/178123198-5bfd58b7-3783-42b3-876b-d6be0e0ab9ff.png)

### EasyEnsembleClassifier
* Balanced accuracy score  0.925%
* Low Risk Precision  1 
* Low Risk Recall 0.94
* High Risk Precision 0.07
* High Risk Recall 0.91

  ![image](https://user-images.githubusercontent.com/99148657/178123206-ca94d48f-4f8f-4d0a-8614-07624ed4821a.png)

## Summary
The analysis shows that all models failed to show strength in classifying high risk accurately and had accuracy scores rannging between 0.5 and 0.9. The most accurate model would be Easy Ensembler Classifier which had the least number of false predictions by a significant level. It also showed the highest accuracy score at 0.925. In cases like credit risk, the lending agency wants to choose a model that minimizes the number of incorrect predictions.





