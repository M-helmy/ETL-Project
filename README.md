# Sales Data
In this project I have used SSIS package to make some simple transformation on the dataset.
First of all, I have used Data Conversion to match the data type
Next, I used Derived Column to add new columns (TotalAmount which calculate the total amount price for each customer)
(LoadDate to get the date of the loading data)
(CleanedCountry and CleanedStatus: I used inner functions UPPER and TRIM to clean the coulumns)
Next, I have used Conditional SPlit to make some filters (you can see it in the screenshots attached)
and Finally, I have gathers all columns with Union All tool and dropped the output in a SQL Server Database

Notice: the dataset I used was generated by an AI tool. (attached)
