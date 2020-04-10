# Janata-Hack
This Hackathon was conducted by Analytics Vidhya on 22/3/2020 and we are supposed to build a Machine Learning Model that detects credit card defaults/frauds done by existing customers.

# Evaluation metric used:

Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

# EDA Steps taken

1. Checking the general statistics associated with the dataset.
2. Checking the correlation to the target.
3. Visualizaing the distribution of all the variables in the dataset.


# Feature Engineering

1. Replacing the values in variable PAY_0 with categorical values as the values are numeric without any labels.
2. Replacing the values in variable PAY_2 with categorical values as the values are numeric without any labels.
3. Replacing the values in variable PAY_3 with categorical values as the values are numeric without any labels.
4. Replacing the values in variable PAY_4 with categorical values as the values are numeric without any labels.
5. Replacing the values in variable PAY_5 with categorical values as the values are numeric without any labels.
6. Replacing the values in variable PAY_6 with categorical values as the values are numeric without any labels.
7. Converting the bill amount with bins of 6 counts.
8. Converting the AGE variable into bins with 6 counts.
9. Standardizing the bill_amount variable and AGE variable and transforming them to fit the data.
10. Creating dummy variables for the dataset.

# Modelling

1. Applied Decision Tree Classifier 
2. Applied Light GBM Classifier 
3. Applied Stratified K Fold with 10 splits
4. Applied XGBoost Classifier
5. Applied Catboost with cross validation


