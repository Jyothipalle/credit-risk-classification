WEEK 20 CHALLENGE- SUPERVISED_LEARNING Author -Jyothi Palle

# credit-risk-classification

# Split the Data into Training and Testing Sets 

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame. 

Created the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. 

Split the data into training and testing datasets by using train_test_split

# Create a Logistic Regression Model 

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model. 

Evaluate the model’s performance by doing the following:

Generated a confusion matrix. 

Generated a classification report. 

# How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Answer: This model has an accuracy score 0.992 which shows that it predicts the health loan and high risk loans really accurate

# Credit Risk Analysis Report :


Classification Report 
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384


Resampled Classification Report
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384


Question: How well does the logistic regression model, fit with oversampled data, predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Answer: With oversampled data the model has an accuracy score 0.994 which shows that it predicts the health loan and high risk loans really accurate. Compared to original data, oversampled data model predicts more accurate high risk loans.


code source :from class activities and Ask BCS hel where needed.
