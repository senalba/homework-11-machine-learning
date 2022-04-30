# Unit 11 - Risky Business
 
![Credit Risk](Images/credit-risk.jpg)

## Background

Mortgages, student and auto loans, and debt consolidation are just a few examples of credit and loans that people seek online. Peer-to-peer lending services such as Loans Canada and Mogo let investors loan people money without using a bank. However, because investors always want to mitigate risk, a client has asked that you help them predict credit risk with machine learning techniques.

In this assignment you will build and evaluate several machine learning models to predict credit risk using data you'd typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so you will need to employ different techniques for training and evaluating models with imbalanced classes. You will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

1. [Resampling](#Resampling)
2. [Ensemble Learning](#Ensemble-Learning)

- - -

## Files

[Resampling Starter Notebook](Starter_Code/credit_risk_resampling.ipynb)

[Ensemble Starter Notebook](Starter_Code/credit_risk_ensemble.ipynb)

[Lending Club Loans Data](Resources/LoanStats_2019Q1.csv.zip)

- - -

## Instructions

### Resampling

# Final Questions

1. Which model had the best adjusted balanced accuracy score?

   * Simple Logistic Regression 0.976
   * __Naive Random Oversampling 0.991__
   * __SMOTE oversampling 0.991__
   * Undersampling 0.988
   * Combination (Over and Under) Sampling 0.99
   

2. Which model had the best recall score?

   * Simple Logistic Regression 0.98
   * __Naive Random Oversampling 1.00__
   * __SMOTE oversampling 1.00__
   * Undersampling 0.99
   * __Combination (Over and Under) Sampling 1.00__
   
3. Which model had the best geometric mean score?

   * Simple Logistic Regression 0.99
   * __Naive Random Oversampling 1.00__
   * __SMOTE oversampling 1.00__
   * Undersampling 0.99
   * __Combination (Over and Under) Sampling 1.00__
   

### Ensemble Learning



### Final Questions

1. Which model had the best balanced accuracy score?

    Easy Ensemble Classifier has adjusted balanced accuracy score 0.86 that is more than adjusted accuracy score of 0.55 for Balanced Random forest.

2. Which model had the best recall score?

    Easy Ensemble Classifier has recall score 0.91 that is more than recall of 0.64 for Balanced Random forest.

3. Which model had the best geometric mean score?

    0.93 > 0.76, better for EEC

4. What are the top three features?

     (total_rec_int, last_pymnt_amnt, total_pymnt)
