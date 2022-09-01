# Credit Risk Analysis

## Analysis Overview:

Evaluating different machine learning models to predict credit risk 

- Over Sampling of Data using RandomOverSampler and SMOTE alogrithms
- Under Sampling using ClusterCentroids algorithm.
- Combining over and under samplying by using SMOTEENN algorithm
- Comparing two ML models Balanced Random Forest Classiffier and Easy Ensemble Classifier. 

## Results

Random Over Sampler Results: 

- Balanced accuracy is 65%
- High Risk percision is about 1%
- Recall is 62% overall. 

![](https://github.com/YuvrajT/Credit-Risk-Analysis/blob/main/Resources/Screen%20Shot%202022-08-29%20at%2016.50.23.png)

- SMOTE over sampling results: Accuracy score is 66.2%, high risk percision is 1% and recall is 69%. 

![](https://github.com/YuvrajT/Credit-Risk-Analysis/blob/main/Resources/Smote.png)

- Under samplying results: balanced accuracy is 66.2, the precision is 99% and lastly recall is 41%

![](https://github.com/YuvrajT/Credit-Risk-Analysis/blob/main/Resources/Undersamplying.png)

- Combination Results: balanced accuracy is 54.7%, the precision is 99% and the recall is 57%

![](https://github.com/YuvrajT/Credit-Risk-Analysis/blob/main/Resources/Balanced.png)

- Balanced Random Forest Classifier: the accuracy score is 77.2%, percision is 99% and recall is 94%

![](https://github.com/YuvrajT/Credit-Risk-Analysis/blob/main/Resources/Forest.png)

- Easy Ensembke Classifier: the accuracy score is 91.7%, percision is 99% and recall is 94%

![](https://github.com/YuvrajT/Credit-Risk-Analysis/blob/main/Resources/Ensemble.png)

## Summary:

Overall, Ensemble Classifier model shows good balance of recall and pericison compared to other models.
