# credit-risk-classification
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Lets get started
    • Ensure you have the following installed on your system:
                •	Python 3.x
                •	Pandas library (pip install pandas)
    • Clone the repository to your local machine: [GitHub Link] (https://github.com/ToniMak70/credit-risk-classification.git)
# Prepare the Data 
    • Import required libraries and dependencies
    • Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
    • Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
    • Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
    • Split the data into training and testing datasets by using train_test_split.

# Create a Logistic Regression Model with the Original Data
* Use your knowledge of logistic regression to complete the following steps:
    • Fit a logistic regression model by using the training data (X_train and y_train).
    • Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
    • Evaluate the model’s performance by doing the following:
        • Generate a confusion matrix.
        • Print the classification report.
        • Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

# Write a Credit Risk Analysis Report
* Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. 
    • An overview of the analysis: Explain the purpose of this analysis.
    • The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
    • A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


## File Structure
credit-risk-classification/
├── Resources/
│   ├── lending_data.csv
├── analysis-report.md
├── credit_risk_classification.ipynb
├── LICENSE
└── README.md


## Acknowledgements
- Classmates: I recieved coding and debuging help from multiple classmates during breakout sessions.
- Internet Search: I utilized Google Search and slack overflow to research coding concepts, algorithms, and best practices.
- Support Staff: I recieved help from my instructor and class TA during office hours for help with debugging errors and further explanation for complex code segments.
- AI support: I leveraged Gemini AI and ChatGPT to generate code suggestions, debug errors, and provide explanations for complex code segments.
- Please note: While these tools were invaluable in my development process, the final code is the result of my analysis, testing, and refinement.