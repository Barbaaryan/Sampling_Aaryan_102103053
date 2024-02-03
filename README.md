# Assignment02 - Sampling
Submitted by: ***Aaryan Gupta***

Roll No: ***102103053***

Group: ***3COE2***

## Dataset
The dataset comprises 31 columns and 772 entries, with a target variable labeled 'Class'. This variable is binary, taking on values of '0' or '1'. The dataset is imbalanced, with 763 entries classified as Class '0' and only 9 entries as Class '1'.
## Balancing the Dataset
I have used SMOTE (Synthetic Minority Oversampling Technique) to balance this dataset. SMOTE works by randomly picking a point from the minority class and computing the k-nearest neighbors for this point. The synthetic points are added between the chosen point and its neighbors. After balancing the dataset, there are 763 entries each of Class '0' and '1'.
## Creating 5 Samples
I have used Simple Random, Systematic, Stratified, Cluster and Bootstrap Sampling Techniques.
## Models Used
I have used Logistic Regression, Random Forest Classifier, Support Vector Classifier, Gradient Boosting Classifier and MLPClassifier.
## Table
![Result](https://github.com/Barbaaryan/Sampling_Aaryan_102103053/blob/main/result.jpg?raw=true)
## Result 
Simple Random Sampling Technique and Random Forest Classifier had the best accuracy. 
