# Credit Risk Analysis
---

## Overview
The purpose of this analysis was to use credit data from a lending service company, LendingClub, to predict credit risk. The outcome of this analysis is meant to assist lending service companies improve their loan application processes by implementing machine learning and identifying optimal loan candidates. Various sampling methods and machine learning models were used to perform analyses on the credit data, including:

- Random Oversampling
- SMOTE Oversampling
- Cluster Centroid Undersampling
- SMOTEENN (Over and Under) Sampling
- Balanced Random Forest Classifying
- Easy Ensemble Classifying

---

## Results
Below are the results for all six machine learning models, including accuracy scores, precision, and recall scores.

#### Random Oversampling
- Accuracy Score: 0.65
- Precision (High Risk): 0.01
- Precision (Low Risk): 1.00
- Recall Score (High Risk): 0.69
- Recall Score (Low Risk): 0.61

![oversamp_accuracy](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/oversamp_accuracy.PNG)

![oversamp_class](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/oversamp_class.PNG)

![oversamp_cm](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/oversamp_cm.PNG)


#### SMOTE Oversampling
- Accuracy Score: 0.66
- Precision (High Risk): 0.01
- Precision (Low Risk): 1.00
- Recall Score (High Risk): 0.63
- Recall Score (Low Risk): 0.69

![smote_accuracy](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/smote_accuracy.PNG)

![smote_class](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/smote_class.PNG)

![smote_cm](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/smote_cm.PNG)


#### Cluster Centroid Oversampling
- Accuracy Score: 0.54
- Precision (High Risk): 0.01
- Precision (Low Risk): 1.00
- Recall Score (High Risk): 0.69
- Recall Score (Low Risk): 0.40

![cc_accuracy](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/cc_accuracy.PNG)

![cc_class](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/cc_class.PNG)

![cc_cm](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/cc_cm.PNG)


#### SMOTEENN (Over and Under) Sampling
- Accuracy Score: 0.68
- Precision (High Risk): 0.01
- Precision (Low Risk): 1.00
- Recall Score (High Risk): 0.78
- Recall Score (Low Risk): 0.57

![smoteenn_accuracy](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/smoteenn_accuracy.PNG)

![smoteenn_class](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/smoteenn_class.PNG)

![smoteenn_cm](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/smoteenn_cm.PNG)


#### Balanced Random Forest Classifying
- Accuracy Score: 0.79
- Precision (High Risk): 0.03
- Precision (Low Risk): 1.00
- Recall Score (High Risk): 0.70
- Recall Score (Low Risk): 0.87

![brf_accuracy](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/brf_accuracy.PNG)

![brf_class](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/brf_class.PNG)

![brf_cm](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/brf_cm.PNG)


#### Easy Ensemble Classifying
- Accuracy Score: 0.93
- Precision (High Risk): 0.09
- Precision (Low Risk): 1.00
- Recall Score (High Risk): 0.92
- Recall Score (Low Risk): 0.94

![eec_accuracy](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/eec_accuracy.PNG)

![eec_class](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/eec_class.PNG)

![eec_cm](https://github.com/AndrewTymkiv/Credit_Risk_Analysis/blob/main/screenshots/eec_cm.PNG)


---

## Summary
After observing the results, it is safe to conclude that the ensemble classifying machine learning methods yielded better results than the oversampling methods, which were not as accurate. One important metric we can observe is the recall scores for high risk loans. The higher the score, the smaller the the number of high risk loans there are that are approved. 
The model with the highest recall score for high rates was the Easy Ensemble Classifying method which yielded a score of 0.92 (92%). The other methods yielded scores between 0.63 and 0.78.
Furthermore, this method also the highest accuracy score of 0.93 (93%). The other methods yielded results between 0.54 and 0.79.

Based on these results, the lending service companies should adopt the Easy Ensemble Classifying machine learning method to detect high risk credit loans as it is the most accurate model out the six observed. 
