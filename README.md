# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of this analysis is in 2019, more than 19 million Americans had at least one unsecured personal loan. That's a record-breaking number! Personal lending is growing faster than credit card, auto, mortgage, and even student debt. With such incredible growth, FinTech firms are storming ahead of traditional loan processes. By using the latest machine learning techniques, these FinTech firms can continuously analyze large amounts of data and predict trends to optimize lending.



## Results:

### Credit Risk Resampling

## Random Over Sampler
Accuracy Score: 65.5%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 70%
Recall Los Risk: 61%

![Random Over Sampler]( RandomOversampler.png)


## SMOTE Oversampling
Accuracy Score: 66.2%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 63%
Recall Los Risk: 69%

![SMOTE Oversampling](SMOTE_Oversampling.png)

## ClusterCentroids resampler
Accuracy Score: 66.2%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 69%
Recall Los Risk: 40%

![ClusterCentroids resampler](ClusterCentroids_resampler.png)
## SMOTEENN
Accuracy Score: 54.4%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 72%
Recall Los Risk: 57%

![SMOTEENN](SMOTEENN.png)

## ------------------------------------------------------------------
### Ensemble Learners

## Balanced Random Forest Classifier
Accuracy Score: 76.9%
Precision High Risk: 3%
Precision Low Risk: 100%
Recall High Risk: 66%
Recall Los Risk: 87%

![ Balanced Random Forest Classifier]( Balanced_Random_Forest_Classifier.png)


## Easy Ensemble Classifier
Accuracy Score: 93.1%
Precision High Risk: 9%
Precision Low Risk: 100%
Recall High Risk: 92%
Recall Los Risk: 94%

![ Easy Ensemble Classifier](Easy_Ensemble_Classifier.png)

![ Resampling Models to Predict Credit Risk](Deliverable1_Resampling_Models_Predict_Credit_Risk.png)
![ SMOTEENN algorithm to Predict Credit Risk](Deliverable_2_SMOTEENN_algorithm_Predict_Credit_Risk.png)
![ Ensemble Classifiers to Predict Credit Risk](Deliverable_3_Ensemble_Classifiers_Predict_Credit_Risk.png)
![Credit Risk Resampling](credit_risk_resampling.png)
![Credit Risk Ensemble](credit_risk_ensemble.png)

## Summary:
After comparing all six machine learning models, my recommendation is to use the “Easy Ensemble Classifier” (credit_resk_ensemble) model due to the Recall of High Risk: 92%.
