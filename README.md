# Customer-Churn-Prediction
Customer's Churn Analysis and Modeling is a comprehensive project focused on understanding and predicting customer churn in the Banking industry. Utilizing advanced data analysis and machine learning techniques, this project aims to provide insights into customer behavior and help develop effective strategies for customer.

![alt img](https://github.com/Aayush-Basnet/Photos/blob/7fa034f7e33f1e0bedbf334fe436a9914331de50/customer%20churn.jpg)

# Problem Statement
Customer churn or customer attrition is a tendency of clients or customers to abandon a brand and stop being a paying client of a particular business or organization. The percentage of customers that discontinue using a company’s services or products during a specific period is called a customer churn rate. Several bad experiences (or just one) are enough, and a customer may quit. And if a large chunk of unsatisfied customers churn at a time interval, both material losses and damage to reputation would be enormous.

A reputed bank “ABC BANK” wants to predict the Churn rate. Create a model by using different machine learning approaches that can predict the best result.


## Dataset Description:

The details about all columns are given in the following data dictionary

Varirable           |  Definition
-------------        | -------------
RowNumber            | Unique Row Number
CustomerId          | Unique Customer Id
Surname            | Surname of a customer
CrediScore        | Credit Score of each Customer
Geography      | Geographical Location of Customers
City_Category     | Category of the City (A,B,C)
Gender       | Sex of Customers
Age         | Age of each Customer
Tenure       | Number of years as member
Balance       | Current Balance of Customers
NumOfProducts     | Number of Products Customers are using
HasCreditCard     | If a Customer has Credit Card
IsActiveMember    | If a customer is active member or not
EstimatedSalary     | Estimated Salary of each Customer
Exit       | Customer left Company or Not



## Working Flow:

In order to create a model these are the following procedure -
  - Split the dataset in 70% of Train set and 30% of Test Set
  - Feature engineering
  - Check the accuracy score for both Training and Test Set
  - Compare the accuracies for both Training and Test set, in order to check for the overfitting issues
