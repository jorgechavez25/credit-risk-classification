# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:


To enhance the accuracy of assessing high-risk applicants and minimize the overall default rate on bank loans, we aim to develop a predictive model that estimates the probability of potential high-risk applicants.


In order to assess the predictive capabilities of our model and determine its accuracy in forecasting loan outcomes, we utilized various categories of historical loan data for training. These categories included loan size, interest rate, borrower income, debt-to-income ratio, number of accounts held by the borrower, derogatory remarks, total debt, and loan status (the final outcome of the loan). By incorporating these diverse factors into our model's training process, we aimed to ascertain its effectiveness in accurately predicting loan outcomes.



Data Preparation was to then select variables to be used in the model. evalute the model as how well it fits the data. Then we test the model on new data to see how accurate it it with predictions.Then draw up conclussion on why it wouild be beste to use/improve on the model.

we used the logestic regreaion to determine a categorical predictions and to term if the data set was fit for the model to predict the outcome.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384





## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
This model works find with whay we are trying to predict but a few tweaks can be make to improve accuracy like to a resampling of the data since it was imbalanced.
 As looking it from a Bank Associate, I would love to see a great accuracy of the high risk loan to determine better practice.


