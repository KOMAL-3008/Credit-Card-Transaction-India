# Credit-Card-Transaction-India 
Data set Link :- https://www.kaggle.com/datasets/thedevastator/analyzing-credit-card-spending-habits-in-india

# Credit Card Transactions in India
This dataset provides a detailed view of credit card transactions across various cities in India. It encompasses critical information to understand spending patterns and financial behavior. The dataset includes the following columns:

Index: A unique identifier for each transaction.
City: The city where the transaction occurred, including Delhi, Greater Mumbai, Bengaluru, Ahmedabad, and more.
Date: The date of each transaction, spanning from 2014 to 2018.
Card Type: The type of credit card used, such as Gold, Platinum, Signature, and Silver.
Expense Type: Categorized types of expenses (e.g., bills, dining, shopping).
Gender: The gender of the cardholder.
Amount: The amount of money spent in each transaction, ranging from modest sums to significant expenditures.

### Key Analyses and Solutions:

# Data Cleaning and Preparation:    
Ensure Data Integrity:
Verify there are no missing or incorrect values in the dataset.
Columns include index, City, Date, Card Type, Expense Type, Gender, and Amount.

# Standardize Data Format:
Format dates and categorical data consistently.

# Descriptive Statistics:
Calculate the Total Number of Transactions:
Method: Use the COUNTA function to count non-empty cells in a selected column to ensure each row represents a transaction.

# Calculate the Total Amount Spent:
Method: Utilize the SUM function to sum all values in the "Amount" column, providing the total spending.

#Find the Average Transaction Amount:
Method: Apply the AVERAGE function to the "Amount" column to determine the average spending per transaction.

# Determine the Number of Transactions per City:
Method: Create a PivotTable with the City field in the Rows area and count the number of transactions using the COUNTA function for a relevant column.

# Trend Analysis:
Analyze Spending Trends Over Time (Monthly, Quarterly, Yearly):
Method: Extract months, quarters, and years from the Date column using Excel functions. Create PivotTables and charts to visualize spending trends over time intervals.

# Identify Peak Spending Periods:
Method: Use PivotTables to analyze total spending per month, quarter, and year to identify the periods with the highest spending.

# Category Analysis:
Compare Spending Habits Based on Card Type (e.g., Gold, Platinum, Silver, Signature):
Method: Use a PivotTable to compare total and average spending amounts for each card type, and create relevant visualizations.

# Compare Spending Habits Based on Expense Type (e.g., bills, dining, shopping):
Method: Configure a PivotTable to analyze spending patterns across different expense types.

# Demographic Analysis:
Analyze Spending Habits Based on Gender:
Method: Create a PivotTable with the Gender field in the Rows area and summarize the Amount field to compare total and average spending between genders.

# Determine if There Are Significant Differences in Spending Between Different Cities:
Method: Create a PivotTable to compare total and average spending by city, and consider statistical analyses for deeper insights.

![Credit Card Dashboard Image](https://github.com/user-attachments/assets/715c6122-5444-4114-b8ba-3a7eecf7831a)


