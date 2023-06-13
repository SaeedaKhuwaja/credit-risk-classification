# Credit Risk Analysis Report

In this Module various techniques of train and test data is used to evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company is used to build a model that can identify the creditworthiness of borrowers. 

## An overview of the analysis:

The purpose is to create a model that can accurately differentiate between 'healthy loan' and 'high risk loan' applicants based on specific factors in their application, such as loan size, interest rate, borrower's income, debt to income ratio, number of accounts, pre-defined derogatory marks, and total debt. The model is then tested to determine its effectiveness in classifying both categories.

## The results:

The results of classification report using original data.

<img width="400" alt="classification-report" src="https://github.com/SaeedaKhuwaja/credit-risk-classification/assets/83857632/7da42037-f8ba-4c6a-9290-bf856301857e">

Based on the classification report, it looks like our model is performing well. The accuracy score of 99% indicates that our model is able to accurately classify the data. The precision score for the riskyloan is 0.87, which means that when our model predicts a positive result, it is correct 89% of the time. The recall score for the positive class is 0.89, which means that our model is able to correctly identify 88% of the positive results. The f1-score for the positive class is 0.88, which is a weighted average of the precision and recall scores. Overall, our model seems to be performing well and is able to classify the data with a high degree of accuracy.

### Analaysis:

The results of classification report using resampled data.

<img width="400" alt="classification-report-1" src="https://github.com/SaeedaKhuwaja/credit-risk-classification/assets/83857632/0fb2c6e3-33dc-4fb4-9106-e5b97bc8ac95">

Based on the classification for resampled data, it looks like our model is performing really well. The accuracy score of 99% indicates that our model is able to accurately classify the data. The precision score for the risky loan is 0.99, which means that when our model predicts a positive result, it is correct 99% of the time. The recall score for the positive class is 0.99, which means that our model is able to correctly identify 99% of the positive results. The f1-score for the positive class is 0.99, which is a weighted average of the precision and recall scores. Overall, our model seems to be performing very well and is able to classify the data with a high degree of accuracy.

## Summary:

The model with an accuracy score of 0.99 is better than the model with an accuracy score of 0.88 although both classify the results with higher degree of accuracy. A model with a higher accuracy score is generally preferred because it is able to make more accurate predictions. However, it is important to note that accuracy is not the only metric that should be considered when evaluating a model's performance. Other metrics such as precision, recall, and f1-score should also be taken into account.



