# credit-risk-classification

I used the internet & worked with classmated to complete this assignment. 

Create a Logistic Regression Model with the Original Data
1. Use your knowledge of logistic regression to complete the following steps:
    a.Fit a logistic regression model by using the training data (X_train and y_train).
    b.Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
    c.Evaluate the model’s performance by doing the following:
        1.Generate a confusion matrix.
        2.Print the classification report.
   d.Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.
Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:
1. An overview of the analysis: Explain the purpose of this analysis.
2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

Requirements
Split the Data into Training and Testing Sets
One must:
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame. 
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. 
3. Split the data into training and testing datasets by using train_test_split. 

Create a Logistic Regression Model 
To receive all points, you must:
1. Fit a logistic regression model by using the training data (X_train and y_train). 
2. Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model. 
3. Evaluate the model’s performance by doing the following:
     a.Generate a confusion matrix. 
     b.Generate a classification report. 
     c.Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels? (5 points)

Write a Credit Risk Analysis Report 
One must:
1. Provide an overview that explains the purpose of this analysis. 
2. Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model. 
3. Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. 

Coding Conventions and Formatting 
To receive all points, you must:
1. Place imports at the top of the file, just after any module comments and docstrings and before module globals and constants. 
2. Name functions and variables with lowercase characters, with words separated by underscores. 
3. Follow DRY (Don’t Repeat Yourself) principles, creating maintainable and reusable code.
4. Use concise logic and creative engineering where possible. 
