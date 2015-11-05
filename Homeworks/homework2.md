# Homework 2

The homework assignment is due before the start of class Thursday 10/8.

This homework is split into two parts, conceptual and practical

### Conceptual

1. What is the difference between train and test set?
2. Why is it important to have a seperate data set for training?
3. What are some advantages and disadvantages of the KNN algorithm?
4. Explain in your own words the bias variance tradeoff.
5. Do you think KNN suffers from high bias or high variance?
6. List some possible solutions when suffering from high variance.
7. List some possible solutions when suffereing from high bias.
8. Would you choose K when doing K Nearest Neighbors?


### Practical


### Data set description 

In this section you will be analysis a data set from (Stamey et al., 1989) on the analysis of prostate cancer. There are 97 obvservations and 8 features corresponding to various clinical measurements.
* lcavol: log(cancer volume) 
* lweight: log(prostate weight) 
* age
* lbph: logarithm of the amount of benign prostatic hyperplasia
* svi: seminal vesicle invasion
* lcp: log(capsular penetration) 
* gleason: Gleason score 
* pgg45: percentage Gleason score 4 or 5

You will be builing a regressor on the above features to try and predict the logarithm of prostate-specific antigen (lpsa)

The data has already been split into a training and test set in the original study. The column train indicates if the example is part of the training or test set. A T in the column train means that observation is a training set and an F in the column indicates it's a test set. 

Stamey, T., Kabalin, J., McNeal, J., Johnstone, I., Freiha, F., Redwine, E. and Yang, N. (1989) Prostate specific
antigen in the diagnosis and treatment of adenocarcinoma of the prostate ii: radical prostatectomy treated
patients. J. Urol., 16, 1076–1083.


### Questions 
1. Perform regression on the prostate data set. Your goal is to minimize the mean squared error (MSE). Split this into a several parts and at a minimum utilize
    * Linear Regression
    * KNN
    * Lasso
    * Ridge 
    * Use cross validation to tune the best model you can
2. Where there any features that were highly correlated?
3. What features were the most important? Unimportant?
4. What model worked best? What was the MSE of each?
5. What difficulties did you have with this data set?

** It's important that you only utilize the training set when doing your analysis. The test set is only used to compute the final MSE. **