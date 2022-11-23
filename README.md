# Credit_Risk_Analysis

## Overview

We are using machine learning to assist Fast Lending predict credit risk. We used the Loan stats dataset and machine learning algorithms to help predict whether an applicant would be approved 

## Results

### Naive Random Oversampling 
![naive.png](https://github.com/1fatpanda1/Credit_Risk_Analysis/blob/main/CRA_Resources/Naive.png)

Naive Random Oversampling had an accuracy of 66.4%, recall 73% high-risk and 59% on low-risk, and sensitivity 1%.

### SMOTE
![smote.png](https://github.com/1fatpanda1/Credit_Risk_Analysis/blob/main/CRA_Resources/smote.png)

Cluster Centroids had an accuracy of 64.1%, recall 60% high-risk and 68% on low-risk, and sensitivity 1%.

### SMOTEENN
![smoteenng](https://github.com/1fatpanda1/Credit_Risk_Analysis/blob/main/CRA_Resources/Smoteen.png)

Cluster Centroids had an accuracy of 63.6%, recall 74% high-risk and 53% on low-risk, and sensitivity 1%.

### Cluster Centroids
![cluester.png](https://github.com/1fatpanda1/Credit_Risk_Analysis/blob/main/CRA_Resources/cluster.png)

Cluster Centroids had an accuracy of 54.5%, recall 67% high-risk and 42% on low-risk, and sensitivity 1%.

## Summary

Overall there was variations between the model. Depending on which attribute one values the most between sensitivity, accuracy, and recall, different models offer better results. 

For this model, Smote had slightly lower accuracy but a much better balance in recall than Naive Random Oversampling. 
