# Machine-Learning
Machine Learning Homework Assignment - Risky Business


![image](https://user-images.githubusercontent.com/99493522/167949737-056ef51e-4562-40ed-a3f7-95f53bea6d13.png)

## Background

Seeking credit and loans online is popular and online lending services always want to mitigate risk. In this project machine learning models will be used to predict credit risk. Credit risk is an inherently imbalanced classification problem, the number of good loans is much larger than the number of at-risk-loans. Therefore imbalanced-learn and Scikit-learn libraries will be used to build and evaluate models. Resampling and ensemble learning techniques will be used.

## Data Sources
These data sources are typically seen in peer-to-peer lending services. 

[Lending_Data](   )

[LoanStats_2019](   )


## Resampling
The data was oversampled using the Naive Random Oversampler and Smote algorithms, undersampled using the Cluster Centroids algorithm and, over and undersampled using a combination SMOTEENN algorithm.
*
### Final Questions

1. Which model had the best balanced accuracy score?

    The Smote Oversampling algorithm and the Cluster Centroid algorithm both had the highest balanced accuracy score of 
    approximately 0.9948. 

2. Which model had the best recall score?

    All the models had an average recall score of 0.99. The Random versampler and the Smote oversampler both had the highest 
    recall score of 1 for high risk. 

3. Which model had the best geometric mean score?

    The best geometric mean score was 0.99 and the Random oversampler, the Smote oversampler and the SMOTEENN all had this score. 
    

## Ensemble Learning
Two different ensemble classifiers (Balanced Random Forest Classifier and Easy Ensemble Classifier) were trained and compared in order to predict loan risk and evaluate each model. 

### Final Questions
1. Which model had the best balanced accuracy score?

    Easy Ensemble Classifier had the best balanced accuracy score of approximately 0.9254 compared to RandomForestClassifier score of approximately 0.6721

2. Which model had the best recall score?

    Based on the avg recall score, Random Forest Classifier had the best score of 1.

3. Which model had the best geometric mean score?

    Easy Ensemble Classifier had the best geometric mean score of 0.93

4. What are the top three features?

    The top three features were, 'total_rec_prncp', 'total_pymnt', and 'total_pymnt_inv'.

## Contributors
Chantal Garnett
