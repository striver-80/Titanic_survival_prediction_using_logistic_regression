# Titanic_survival_prediction_using_logistic_regression
A simple titanic survival project using logistic regression
## Brief about dataset:
This dataset is taken from kaggle. To know about the dataset go to the below link:
https://www.kaggle.com/c/titanic.
The training dataset is from the file train.csv.
The test dataset is from the file test.csv.
The test data of target variables is collected from gender_submission.csv where gender_subission.csv is a file with an assumption that all female passengers have been survived.

## Dealing with missing values:
The column cosists of more than 50% missing data has been dropped and the other column with lower number of missing values have been replaced by the mean value of the respective column.

## Data Preprocesing:
For the important columns with categorical value have been replaced with numerical values for training purpose. (E.g male is replaced with 1 and female is replaced with 0)

## Model Training
For model traning I have used Logistic Regression from sklearn module with iteration number 1000 i.e max_iter = 1000.

## Model Evaluation:
The model is evaluated on the basis of the accuracy_score and on the basis of confusion matrix.

## Performance:
The predicted values for training dataset and for test dataset have been saved in the train_submission.csv and test_submission.csv files respectively.
