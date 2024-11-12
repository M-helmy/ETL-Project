# Sales Data

#Tools:

SSIS
SQL Server

Dataset:
it's a generated data by AI tool and it contains data customers and thier purchases.

Objective:
Calculating the total amount for each customer for each purchase he made and validating the dataset for missing and outliers values.

#Steps:

loaded the dataset into SSIS, I have used Data COnversion tool to match the data types.

Utlitzed Derived Column Transformation to generate the TotalAmount (calculating the total price for each customer), LoadData (to get the time the datahas loaded), CLeanedCountry and CleanedStatus (I used Upper and Trim function to modify columns data) columns.

Leveraged Conditional Split to filter out the data from the missing and outliers values.

Gatherd all the output through Union All Transformation and load the data into SQL Server Database.
