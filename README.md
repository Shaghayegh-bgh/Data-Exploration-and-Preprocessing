# Data-Exploration-and-Preprocessing

## Code Explanation

This code loads data from an Excel file named stock.xlsx into a pandas DataFrame and then converts it into a NumPy array to display basic information such as the number of rows, columns, dimensions, and total elements.

It checks for missing values (nulls) in the dataset and fills them as follows:

For the CustomerID column, missing values are replaced with the string "Unknown" due to the large number of missing entries.

For the Description column, missing values are replaced with "No Description".

Next, the code inspects the data types in each column and identifies if any column contains mixed data types (e.g., both numbers and strings). It prints a warning if mixed types are found along with their counts.

Finally, to ensure consistency and facilitate further processing, the columns InvoiceNo, StockCode, and Description are explicitly converted to string type.
