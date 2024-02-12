Personal Savings Dashboard

Main file is Savings dashboard.xlsx
--Update Data Source location for transactions.csv and categories.csv files in main file.

Business issue

The stakeholder has main goals

Save and invest money
Hold third-party money
Track bank accounts
Make short-term savings

He has a personal Excel file where he enters all transactions referring to his savings operations. 

It was agreed that the stakeholder wanted to track answers to the following questions in one place

Has he entered all transactions correctly?
How much money was saved?
Does he save this month according to the plan?
How much third-party money does he keep in his accounts?
If he is on track with short-term goals?
How is his money distributed by investment types?
How is his money distributed by currencies?
How much money is in his savings bank account?

It has been agreed to create a dashboard that represents the metrics needed to answer all his questions.

Result

Dashboard Design and implementation

Data source

This sample data contains 2 files

transactions.csv 
contains all transactions
categories.csv
contains supporting information referred to the category of transaction

Data preparations:

Data load and transformation with Power Query, language M
Data range check, duplication, empty rows lookup and clearing
Date transformation: extending data model with extra columns
Date, Number formatting

Data processing/analysis

Date, Number formatting
Pivot tables
Slicers
Pivot Charts
Styling
Power Query Merge
Functions








