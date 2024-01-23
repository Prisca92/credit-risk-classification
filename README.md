Credit-Risk Analysis Overview:

The purpose of this analysis is to create and evaluate a model based on loan risk using data of historical lending activity from a lending service company in order to build a model that can identify the creditworthiness of borrowers. I was given the task to  split the Data into Training and Testing Sets by reading the lending_data.csv data from the Resources folder into a Pandas Data Frame. Then creating labels set (y) from the “loan_status” column, I then created the features (X) Data Frame from the remaining columns. Following that I then create a Logistic Regression Model with the Original Data. I needed to fit a logistic regression model by using the training data (X_train and y_train). I then saved the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model. And finally evaluated the model’s performance by generating a confusion matrix and generating a classification report.

Financial Information:
Interest rate
Borrower income
Borrower debt to income ratio
Borrower total debt
Dollar amount loan
 Amount of credit accounts the borrower has
Number of derogatory marks against the borrower 

Results 

Machine Learning Model 1:
•	Accuracy score = 0.99
•	Precision score = (0) = 1.00, (1) =0.85
•	Recall score = (0) = 0.99, (1) =0.91

Machine Learning Model 2:
•	Accuracy score = 0.99
•	Precision score: (0) = 1.00, (1) =0.84
•	Recall score: (0) = 0.99, (1) =0.99


Summary: 
Two models were generated while conducting this analysis to determine which model fit best. Both models displayed an adequate fit. However, machine learning model 2 performed best as I noticed more improvements in regards to accuracy and recall score.
![image](https://github.com/Prisca92/credit-risk-classification/assets/140542648/0a7bd16c-d86b-46aa-892b-7a1a852d10f3)
