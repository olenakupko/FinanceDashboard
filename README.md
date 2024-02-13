# Personal Savings Dashboard

## Main File: Savings dashboard.xlsx

- **Update Data Source location for transactions.csv and categories.csv files in Savings dashboard.xlsx.**
- Data->Queries&Connections->Queries list->Edit "Savings" query->
    --Change the path to Transactions.csv in the "Source" step

- Data->Queries&Connections->Queries list->Edit "Categories" query->
    --Change the path to Catgories.csv in the "Source" step

# Personal Savings Dashboard with EXCEL

## Business Issue

A client has a file where he writes and tracks all personal saving money transactions for one year. He spends much time entering and checking the integrity of entered information. He wants to make this process faster. Also, he needs to see in one place the state of his savings.

It was clarified that the client has main goals:

- Save and invest money
- Hold third-party money
- Track savings bank accounts
- Make short-term savings

Every month the client updates his files with transactions. After each update, he needs to see answers to the following questions in one place:

1. Has he entered all transactions correctly?
2. How much money was saved?
3. Does he save this month according to the plan?
4. How much third-party money does he keep in his accounts?
5. On which bank accounts and in which currencies are third-party money located?
6. Is he on track with short-term goals?
7. What is the trend over time of his savings?
8. What is the breakdown of his money for investments by investment type?
9. What does each investment type consist of?
10. How much money is in his savings bank accounts?


### Data Source

This sample data contains 2 files. All data are anonymized:

1. **transactions.csv**: contains all transactions
2. **categories.csv**: contains supporting information referred to the category of transaction

### Used Features:

#### Data Preparations:

- Data load and transformation with Power Query, language M
- Data range check, duplication, empty rows lookup, and clearing
- Date transformation: extending data model with extra columns
- Date, Number formatting
- Data Anonymization

#### Data Processing/Analysis

- Date, Number formatting
- Pivot tables
- Slicers
- Pivot Charts
- Slicer, Pivot table styling
- Power Query Merge
- Functions: FILTER, IF, DATE_DIF, AND, etc.

The implementation of the DashBoard results

The using of the DashBoard decreased the time to enter data and check the correctness by 16% from an average of 90 minutes to 75 minutes.
