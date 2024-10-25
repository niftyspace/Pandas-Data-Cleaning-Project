Customer Dataset Cleaning with Pandas

Description
This project demonstrates data cleaning techniques using Python's Pandas library. The dataset contains customer information, including phone numbers, addresses, and status fields (e.g., paying customers and contact preferences). The objective is to clean the dataset for further analysis by:

Standardizing phone numbers.
Removing unnecessary columns.
Handling missing values.
Dataset Overview
The dataset includes the following columns:

CustomerID: Unique identifier for each customer.
First_Name and Last_Name: Customer's name.
Phone_Number: Contact number (cleaned and standardized).
Address: Customer’s address.
Paying Customer: Whether the customer is paying or not.
Do_Not_Contact: Indicates customers who prefer not to be contacted.
Not_Useful_Column: An unnecessary column removed during cleaning.
Steps Performed
Loaded the dataset using Pandas
Standardized Phone Numbers
Removed special characters (e.g., /, |, -) to keep only numeric values.
Filled or dropped missing values in critical fields.
Dropped the Not_Useful_Column since it wasn't relevant for analysis.
Identified and removed duplicate records (e.g., Anakin Skywalker entry).
Exported the cleaned data to cleaned_dataset.csv.

Technologies Used
Python
Pandas
Jupyter Notebook

How to Contribute
Feel free to fork this repository and open a pull request with your improvements!
