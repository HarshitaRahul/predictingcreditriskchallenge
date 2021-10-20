# predictingcreditriskchallenge

With the given data for the year 2019 and quarter of 2020 , target column being loan_status which is y for both train and test shows that after running get dummies on X to get categorical data ,we find  there is a difference in columns in test data .


Using LabelEncoder for y data rather than get dummies

Comparing Logistic Regression and RandomClassifier for the unscaled data and scaled data
With LR giving us only 50% with the number of iterations reached to its limit and 65% on training set which is overfitting but whereas random randomclassifier giving us 63% on testing and giving 100% on training data which is overfitting so it is not accurate.

Performing LR and RC on scaled data where  LR ->we are getting 75% for test and71% for training data which is not overfitting
RC -> 63% on testing and giving 100% on training data which is overfitting


Logistic Regression is best compared to randomclassifiers to predictcreditrisk.