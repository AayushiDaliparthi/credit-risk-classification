# credit-risk-classification

**Overview**

The purpose of this analysis is to develop a logistic regression model to predict the credit risk of loans. Specifically, the model aims to classify loans into two categories: healthy loans (0) and high-risk loans (1). By evaluating the model's performance, we can determine its suitability for identifying high-risk loans and assist financial institutions in making informed lending decisions.

Results

Accuracy, Precision, and Recall Scores
Accuracy: The overall accuracy of the model, indicating the proportion of correct predictions among the total number of cases.
Precision (Healthy Loans - 0): The proportion of true healthy loans among all loans predicted as healthy.
Recall (Healthy Loans - 0): The proportion of actual healthy loans correctly identified by the model.
Precision (High-Risk Loans - 1): The proportion of true high-risk loans among all loans predicted as high-risk.
Recall (High-Risk Loans - 1): The proportion of actual high-risk loans correctly identified by the model.
Performance Metrics:

For Healthy Loans (0):

Precision: 100%
Recall: 100%
For High-Risk Loans (1):

Precision: 87%
Recall: 89%
Summary
The logistic regression model demonstrates excellent performance in predicting healthy loans, with both precision and recall at 100%. This indicates that the model is highly reliable in identifying loans that are not at risk of default.

For high-risk loans, the model shows good performance with a precision of 87% and a recall of 89%. While these scores are strong, they indicate some potential for false positives (loans incorrectly classified as high-risk) and false negatives (high-risk loans incorrectly classified as healthy).

Recommendation
Given the model's high performance in predicting healthy loans and its reasonably good performance in predicting high-risk loans, it can be recommended for use by the company. The model's ability to accurately identify healthy loans can help minimize unnecessary scrutiny of low-risk applicants. However, there is room for improvement in identifying high-risk loans, and further tuning or incorporating additional features could enhance the model's performance in this area.

Overall, this logistic regression model provides a solid foundation for credit risk analysis and can be a valuable tool for the company's decision-making process.

Instructions

Split the Data into Training and Testing Sets
Read Data: Load the lending_data.csv file into a Pandas DataFrame.
Create Labels and Features:
Labels (y): Extract the "loan_status" column.
Features (X): Use the remaining columns.
Split Data: Use train_test_split to divide the data into training and testing sets.
Create a Logistic Regression Model with the Original Data
Fit Model: Train a logistic regression model using the training data (X_train and y_train).
Predict: Save predictions for the testing data labels using X_test and the fitted model.
Evaluate:
Generate a confusion matrix.
Print the classification report.
Assess how well the model predicts both healthy (0) and high-risk (1) loans.
Write a Credit Risk Analysis Report
Overview: Explain the purpose of the analysis.
Results: Summarize the accuracy, precision, and recall scores of the model.
Summary: Provide a conclusion on the model's performance and recommendation for use.
Code Conventions and Formatting

Imports: Place imports at the top of the file.
Naming: Use lowercase characters with underscores for function and variable names.
DRY Principles: Avoid code repetition and create maintainable, reusable code.
Concise Logic: Apply creative and concise engineering practices.
Code Comments

Ensure the code is well-commented with concise, relevant notes for other developers to understand.