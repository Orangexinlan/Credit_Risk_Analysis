# Credit Risk Analysis

## Analysis Overview:

Credit risk is very tough to predict. In this project we want to take a look at how all the factors in our loan_stats csv help predict whether someone is low or high risk status. One method that data scientists use for this type of issue is creating a model and then evaluate and train the models that they create. In this specific project we are using imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. In the first couple of models I oversampled the data using randomoversampler and smote algorithms and undersample the data with the clustercentroid algorithm. In the remaining models I used a combination approach to over and undersample the data using smoteenn. Finally, I compared two machine learning models that minimize bias, balancedrandomforestclassifier and easyensembleclassifier. 

## Results

Random Over Sampler Results: 

- Balanced accuracy is 65%
- High Risk percision is about 1%
- Recall is 62% overall. 

![this is an image](https://github.com/Orangexinlan/Credit_Risk_Analysis/blob/b1e250d7db7663c5cd94ed7877dae98fbcc9761f/Resources/SS.png)

- SMOTE over sampling results: Accuracy score is 66.2%, high risk percision is 1% and recall is 69%. 

![this is an image](https://github.com/Orangexinlan/Credit_Risk_Analysis/blob/b1e250d7db7663c5cd94ed7877dae98fbcc9761f/Resources/Smote.png)

- Under samplying results: balanced accuracy is 66.2, the precision is 99% and lastly recall is 41%

![this is an image](https://github.com/Orangexinlan/Credit_Risk_Analysis/blob/b1e250d7db7663c5cd94ed7877dae98fbcc9761f/Resources/Undersamplying.png)

- Combination Results: balanced accuracy is 54.7%, the precision is 99% and the recall is 57%

![this is an image](https://github.com/Orangexinlan/Credit_Risk_Analysis/blob/b1e250d7db7663c5cd94ed7877dae98fbcc9761f/Resources/Balanced.png)

- Balanced Random Forest Classifier: the accuracy score is 77.2%, percision is 99% and recall is 94%

![this is an image](https://github.com/Orangexinlan/Credit_Risk_Analysis/blob/b1e250d7db7663c5cd94ed7877dae98fbcc9761f/Resources/Forest.png)

- Easy Ensembke Classifier: the accuracy score is 91.7%, percision is 99% and recall is 94%

![this is an image](https://github.com/Orangexinlan/Credit_Risk_Analysis/blob/b1e250d7db7663c5cd94ed7877dae98fbcc9761f/Resources/Ensemble.png)

## Summary:

In reviewing all six models, the EasyEnsembleClassifer model yielded the best results with an accuracy rate of 93.2% and a 9% precision rate when predicting "High Risk candidates. The sensitivity rate (aka recall) was also the highest at 92% compared to the other models. The result for predicting "Low Risk" was also the highest with the sensitivity rate at 94% and an F1 score of 97%. Therefore, if a model needed to be recommended to perform this type of analysis, then this one would be the clear choice.
