# CreditCardDefaultersPrediction

## Problem Statement:To build a classification methodology to determine whether a person defaults the credit card payment for the next month, it used for the purpose of many things including creating new strategies and policies.

## Architechture:

## Data Description:
    >in multiple sets of files in batches at a given location. The data has been extracted from the census bureau
    > 32561 instances in the dataset
    > 8 independent features(Total-23)
    > Target label consist of two classes, default payment next month:
                                            Yes-1,No-0
## Data Validation:
In this step, we perform different sets of validation on the given set of training files.
Data validation includes:
    1-Name Validation:We are validating the name of  files based on the schema data.We have created a regex pattern as per the name given in the schema file to use for validation. 
    2-Number of Columns: We are validating the number of columns based on the amount of columns mentioned inside the schema file
    3-Name of Columns:Validation name of the columns which is same as the schma file
    4-The datatype of columns: Checking the datatype of columns by comparing with schema file and make sure it is same.
    5-Null values in columns :checking for null values and validating it.

## Data Insertion in DB:
Here we are doing Insertion process of data into database:
    1-Database Creation and connection 
    2-Table creation in the database 
    3-Insertion of files in the table:Good data into Good_data_Folder and bad data into Bad_Data_Folder 