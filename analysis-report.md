# Module 12 Report Template
## Overview of the Analysis
This analysis focuses on constructing a predictive model using financial data to classify loan applicants into healthy or high-risk categories, specifically predicting the likelihood of loan default. 

The dataset contained financial information for loan applicants, including loan size, interest rate, income, debt-to-income ratio, account history, derogatory marks, and total debt. The goal was to predict loan default, classifying loans as high-risk.

The analysis proceeded through several key stages of the machine learning process. First, I performed data cleaning and exploratory data analysis to understand the dataset. Next, I selected the features (X) and target variable (y) for our model. The data was then split into training and testing sets. Subsequently, I trained the chosen model using the training data and evaluated its performance on the unseen test data, employing appropriate metrics.

I used Logistic Regression, a binary classification algorithm, to predict loan status.


## Results
* Machine Learning Model 1:
    •	Accuracy: 99% --> A 99% balanced accuracy demonstrates the model's strong ability to accurately classify both positive and negative outcomes.
    •	Precision: 93% --> This indicates that 93% of the model's positive predictions were accurate.
    •	Recall: 95% --> The model successfully detected 95% of all instances that were truly positive.

## Summary
To effectively predict borrower creditworthiness, I suggest using this model. Its high accuracy rate of over 95% in predicting loan repayment outcomes allows lenders to build risk profiles that will help to ensure proper capital flow.


