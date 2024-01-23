Credit-Risk Analysis Overview:

The purpose of this analysis is to create an evaluate a model based on loan risk using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. I was given the task to first Split the Data into Training and Testing Sets by reading the lending_data.csv data from the Resources folder into a Pandas DataFrame. Then creating labels set (y) from the “loan_status” column, I then created the features (X) DataFrame from the remaining columns.

The following step as to create a Logistic Regression Model with the Original Data. I first needed to fit a logistic regression model by using the training data (X_train and y_train). Then save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model. And finally evaluate the model’s performance by generating a confusion matrix and generate a classification report.
Financial Information:



The results: 

Machine Learning Model #1:
Accuracy score = 0.99
Precision score = 
(0)= 1.00
(1)=0.85
Recall score =
(0)= 0.99
(1)=0.91

Machine Learning Model #2:
Accuracy score = 0.99
Precision score :
(0)= 1.00
(1)=0.84
Recall score :
(0)= 0.99
(1)=0.99


Summary: 
Two models were generated while conducting this analysis to determine which model fit best. Both models displayed an adaquate fit. However, machine learning model 2 performed best as I noticed more imporevement in regards to accuracy and recall.


File Location: Assignment can be found in the credit-risk folder titled :

