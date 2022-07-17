# Credit Risk Analysis
The ovbojective of this project was to leverage Machine Learning to determin at risk lendees in order to ensure that only qualified individuals were recieiving credit. This analysis factored in several variables to make these determinations. Additionally, several different methods of machine learning were used 

## Mehtods and Results
- RandomOverSampler: 65.33%
- SMOTE: 65.7%
- ClusterCentroids: 69.8%
- SMOTEEN: 51.03%
- BallancedRandomForest: 99.23%
- EasyEnsembleClassifier: 99.28%

## Summary
I belive that in order to most accurately predict credit worthiness we should use the ClusterCentroids model as this will not require boosting and can be widley used for various samples. 

![IMAGE](https://github.com/mmilner3/credit_risk_analysis/blob/main/Capture.PNG)