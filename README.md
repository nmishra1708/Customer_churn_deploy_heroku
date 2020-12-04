# Project Report 

## CAPSTONE Using Python
Domain of project – Telecom

## Problem Statement –
You are the Data Scientist at a telecom company “Neo” whose customers are churning out to its competitors. You have to analyse the data of your company and find insights and stop your customers from churning out to other telecom companies.

## Customer_churn Dataset:

The details regarding this ‘customer_churn’ dataset are present in the data dictionary
#### customerID : Its shows the unique Customer ID	
#### gender: Its specify the gender status of customer
#### SeniorCitizen: It represent the customer is senior citizen or not
#### Partner	Dependents: Its show the partner dependancy in two category	
#### tenure: Its Specify the tenure of service opt	
#### PhoneService: Its specify the phone service opt or not
#### MultipleLines: Its specify the multiplelines service or not
#### InternetService: Its specify which service opt by customer
#### OnlineSecurity: Its specify the security either yes or no
#### OnlineBackup: Its shows either yes or no
#### DeviceProtection:Its shows either yes or no	
#### TechSupport: Its specify techsupport opt by customer or not
#### StreamingTV: Its specify the status of tv streaming	
#### StreamingMovies: Its specify the status of movies streaming
#### Contract: Its show the period of contract	
#### PaperlessBilling: Its shows the billing either paperless or with paper	
#### PaymentMethod: Its specify the payment method
#### MonthlyCharges: Its specify monthly charges 
#### TotalCharges: Its specify total charges	
#### Churn: Its specify the status of customer churn out service or not

## Lab Environment: 
Jupyter Notebook, python 3.6

## Implementation Details:
We have devided project implementation in six consecutive module, desciption of each module shown below:

## Module-1 
  + A) Data Manipulation:
    +  a.	Extract the 5th column & store it in ‘customer_5’
    +  b.	Extract the 15th column & store it in ‘customer_15’
    +  c.	Extract all the male senior citizens whose Payment Method is Electronic check & store the result in ‘senior_male_electronic’
    +  d.	Extract all those customers whose tenure is greater than 70 months or their Monthly charges is more than 100$ & store the result in ‘customer_total_tenure’
    +  e.	Extract all the customers whose Contract is of two years, payment method is Mailed check & the value of Churn is ‘Yes’ & store the result in ‘two_mail_yes’
    +  f.	Extract 333 random records from the customer_churndataframe& store the result in ‘customer_333’
    +  g.	Get the count of different levels from the ‘Churn’ column

## Module-2 
  +  B) Data Visualization:
    +  a.	Build a bar-plot for the ’InternetService’ column:
      +  i.	Set x-axis label to ‘Categories of Internet Service’
      +  ii.	Set y-axis label to ‘Count of Categories’
      +  iii.	Set the title of plot to be ‘Distribution of Internet Service’
      +  iv.	Set the color of the bars to be ‘orange’

    +  b.	Build a histogram for the ‘tenure’ column:
      +  i.	Set the number of bins to be 30
      +  ii.	Set the color of the bins  to be ‘green’
      +  iii.	Assign the title ‘Distribution of tenure’
  
    +  c.	Build a scatter-plot between ‘MonthlyCharges’ & ‘tenure’. Map ‘MonthlyCharges’ to the y-axis & ‘tenure’ to the ‘x-axis’:
      +  i.	Assign the points a color of ‘brown’
      +  ii.	Set the x-axis label to ‘Tenure of customer’
      +  iii.	Set the y-axis label to ‘Monthly Charges of customer’
      +  iv.	Set the title to ‘Tenure vs Monthly Charges’
  
    +  d.	Build a box-plot between ‘tenure’ & ‘Contract’. Map ‘tenure’ on the y-axis & ‘Contract’ on the x-axis. 


## Module-3
  +  C)	Linear Regression:
    +  a.	Build a simple linear model where dependent variable is ‘MonthlyCharges’ and independent variable is ‘tenure’
      +  i.	Divide the dataset into train and test sets in 70:30 ratio. 
      +  ii.	Build the model on train set and predict the values on test set
      +  iii.	After predicting the values, find the root mean square error
      +  iv.	Find out the error in prediction & store the result in ‘error’
      +  v.	Find the root mean square error

## Module -4
  +  D)	Logistic Regression:
    +  a.	Build a simple logistic regression modelwhere dependent variable is ‘Churn’ & independent variable is ‘MonthlyCharges’
      +  i.	Divide the dataset in 65:35 ratio
      +  ii.	Build the model on train set and predict the values on test set
      +  iii.	Build the confusion matrix and get the accuracy score

    +  b.	Build a multiple logistic regression model where dependent variable is ‘Churn’ & independent variables are ‘tenure’ & ‘MonthlyCharges’
      +  i.	Divide the dataset in 80:20 ratio
      +  ii.	Build the model on train set and predict the values on test set
      +  iii.	Build the confusion matrix and get the accuracy score

## Module-5
  +  E)	Decision Tree:
    +  a.	Build a decision tree model where dependent variable is ‘Churn’ & independent variable is ‘tenure’
      +  i.	Divide the dataset in 80:20 ratio
      +  ii.	Build the model on train set and predict the values on test set
      +  iii.	Build the confusion matrix and calculate the accuracy

## Module-6
  +  F)	Random Forest:
    +  a.	Build a Random Forest model where dependent variable is ‘Churn’ & independent variables are ‘tenure’ and ‘MonthlyCharges’
      +  i.	Divide the dataset in 70:30 ratio
      +  ii.	Build the model on train set and predict the values on test set
      +  iii.	Build the confusion matrix and calculate the accuracy


# Capstone_heroku_deploy
# Capstone_Project_for_Heroku_Final
# Capstone_Project_for_Heroku_Final
