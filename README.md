# Credit_Risk_Analysis

## Overview of the analysis

The purpose of this analysis is to apply machine learning to solve a real-world challenge: credit card risk. As credit risk is an unbalanced classification problem, the good loans outnumber the risky loans. The different techniques will help evaluate the performance of the models and only some should be used to predict credit risk.

## Results

- Naive Random Oversampling
![Naive](url)
The balanced accuracy score of Naive Random Oversampling was 0.66 and the avg of the precision and recall scores are 0.99 and 0.61 respectively.

- Smote Oversampling
![Smote](url)
The balanced accuracy score of Smote Oversampling was 0.65 and the avg of the precision and recall scores are 0.99 and 0.68 respectively.

- Undersampling
![Undersampling](url)
The balanced accuracy score of Undersampling was 0.65 and the avg of the precision and recall scores are 0.99 and 0.41 respectively.

- Combination (Over and Under Sampling)
![Combination](url)
The balanced accuracy score of Combination (Over and Under Sampling) was 0.54 and the avg of the precision and recall scores are 0.99 and 0.55 respectively.

- Balanced Random Forest Classifier
![Balanced](url)
The balanced accuracy score of Balanced Random Forest Classifier was 0.79 and the avg of the precision and recall scores are 0.99 and 0.88 respectively.

- Easy Ensemble AdaBoost Classifier
![Easy](url)
The balanced accuracy score of Easy Ensemble AdaBoost Classifier was 0.93 and the avg of the precision and recall scores are 0.99 and 0.94 respectively.

## Summary

The majority of the machine learning models did not output impressive balanced accuracy scores. There was one with the highest score of 0.93 which was Easy Ensemble AdaBoost Classifier adn would recommend this model to be used. 