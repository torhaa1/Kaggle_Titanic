# Titanic ML competition

The Titanic ML competition on Kaggle is a challenge made for practitioners to explore machine learning techniques and familiarize themselves with the how the Kaggle platform works. The dataset is small, imbalanced and contains missing values, which makes it a good dataset to practice data preprocessing and feature engineering techniques.

A binary classification problem is presented, where the goal is to predict whether a passenger survived or not. The dataset is split into two files: train.csv and test.csv. The train.csv file contains the training data, while the test.csv file contains the test data. The test data does not contain the Survived column, which is the target variable. The goal is to predict the Survived column for the test data.

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

---

### Resulting Model Performance

| Model                | Accuracy | Accuracy       | Test set  | Test set   |
|----------------------|----------|----------------|-----------|------------|
|                      | Baseline | Tuned model    | 1st submission | reduced overfit |
| Logistic Regression  | 80.5     | 80.9           | 74.880    | 75.598     |
| Random Forest subset | 78.7     | 80.0           | 77.751     | 77.272     |
| Random Forest all    | 82.2     | 82.4           | 76.315    | 77.990     |
| SVM                  | 82.4     | 81.7           | 66.985    | 77.751     |
| XGBoost              | 82.0     | 83.7           | 76.076    | 76.555     |
| Gradient Boosting    | 82.3     | 83.4           | 76.315    | 77.272     |

The Random Forest model performed best with an accuracy of 77.99% on the test set (top 22.3%).