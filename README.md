# Titanic dataset
## Binary classification problem

The Titanic dataset present a binary classification problem, where the goal is to predict whether a passenger survived or not. 

The dataset is split into two files: train.csv and test.csv. The train.csv file contains the training data, while the test.csv file contains the test data. The test data does not contain the Survived column, which is the target variable. The goal is to predict the Survived column for the test data.

Notes: 
- The dataset is small, with only 891 samples in the training data.
- The dataset is imbalanced, with 549 samples of class 0 and 342 samples of class 1.
- The dataset contains missing values that need to be handled
- The dataset contains categorical variables that need to be encoded

The dataset is available on [Kaggle](https://www.kaggle.com/c/titanic) and contains the following columns:

| Variable | Definition                          | Key                        |
|----------|-------------------------------------|----------------------------|
| survival | Survival                            | 0 = No, 1 = Yes            |
| pclass   | Ticket class                        | 1 = 1st, 2 = 2nd, 3 = 3rd  |
| sex      | Sex                                 |                            |
| Age      | Age in years                        |                            |
| sibsp    | # of siblings / spouses aboard the Titanic |                    |
| parch    | # of parents / children aboard the Titanic |                    |
| ticket   | Ticket number                       |                            |
| fare     | Passenger fare                      |                            |
| cabin    | Cabin number                        |                            |
| embarked | Port of Embarkation                 | C = Cherbourg, Q = Queenstown, S = Southampton |


