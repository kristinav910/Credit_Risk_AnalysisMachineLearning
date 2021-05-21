# Credit Risk Analysis Machine Learning
Completed 2 exercises in risk analysis for lending methods using machine learning models to predict credit risk. 
## Exercise 1
### Resampling
Employed 3 methods of resampling data for predictions: 
- Oversampling, using the Naive Random Oversampler and SMOTE algorithms
- Undersampling, using the Cluster Centroid algorithm
- Combination sampling, using the SMOTEEN algorithm <lb>

Created logistic regression classifier, balanced accuracy score, confusion matrix and imbalanced classification report for each sampling method 

### Questions:
1. Which model had the best balanced accuracy score? 
    - SMOTE oversampling method had highest with .65
2. Which model had the best recall score?
    - SMOTE oversampling method had highest with .68
3. Which model had the best geometric mean score?
    - SMOTE oversampling method had highest with .65

## Exercise 2
Trained and compared 2 different ensemble classifiers to predict loan risk. Used Balanced Random Forest and Easy Ensemble Classifiers to complete the analysis. 
Created imbalanced classification report, balanced accuracy score, confusion matrix for each sampling method. Also sorted features by order of importance for the Balanced Random Forest Classifier. 
#### Questions
1. Which model had the best balanced accuracy score?
    - EEC had the best with .92
2. Which model had the best recall score?
    - EEC had the best with .94
3. Which model had the best geometric mean score?
    - EEC had the best with .92
4. What are the top three features?
    - The top three features were Total_Rec_Prncp, last_pymnt_amnt, and total_pymnt_inv
