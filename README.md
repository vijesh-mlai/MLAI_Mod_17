# MLAI_Mod_17
Repository for Module 17 - Practical Application -3 
## Assigment Name
## Bank Deposit Subscription Prediction.

This project aims to predict if the customer would open a deposit subscribtion in the bank based on customer campaign calls.

## Some of the key Features included in the dataset are:
- Duration of call
- Age
- Education
- Marital Status
- Job
- Campaign

## Assignment Objective

To Apply various classification methods to a business problem and Compare the results of k-nearest neighbors, logistic regression, decision trees, and support vector machines.

## Summary of the findings for Assignemnt - 

### Overview
- Executed various machine learning models on the Portugal - Deposit Subscription Dataset, comparing their metrics including accuracy, precision, recall, F1-score, and the corresponding runtime of each model.

### Key Observations
1. This was an Imbalanced Dataset there by we are not focusing much on the Accuracy Value of all the evaluated models.
2. SVC and SVC with Hyper Parameter tuning showed significant runtime differences.
3. Highest test accuracy was seen for Decision Tree Classifier when used with GRID Search CV.
4. DecisionTreeClassifier have extreme differences between train and test there by displaying overfitting on the data.
5. Logistic Regression showed balanced precision/recall metric.
6. The dataset with SVC models demonstrated better precision than recall metric output.
7. DecisionTreeClassifier with out any parameters showed severe overfitting.
8. KNN models showed moderate overfitting
9.SVC Grid-CV showed the least overfitting but with bad recall metric values.

### Inference
- From the dataset provided and with all the transformations performed on the data SVC performed better when compared with other Models. Though we still need to make the recall performance better. SVC can be used to predict the outcome on the Deposit Subscription dataset.

## Jupyter Notebook Link
- https://github.com/vijesh-mlai/MLAI_Mod_17/blob/main/prompt_III.ipynb

