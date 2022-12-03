# Amazon_Vine_Analysis
Overview of the analysis:

The objective of this assignment is to pick a dataset from the list of AWS datasets given to us. I picked the Video Games dataset for my analysis.

VideoGames Dataframe:
![alt text](Resources/VideoGamesDF.png)

### Deliverable 1:

- Created an RDS database called "DataViz"
- Defined inbound and outbount security rules in the RDS cosole to be able to connect to the database from PGAdmin 4
- Used PySpark functions to get dataframe information and perform ETL process on the data.

Created the following data frames:


Customers Dataframe:
![alt text](Resources/CustomersTableDF.png)

Products Dataframe:
![alt text](Resources/ProductsDF.png)

Review ID Dataframe:
![alt text](Resources/ReviewTableDF.png)

Defined connection String from colab worksheet and inserted data from the dataframes to RDS database and verified data from PGAdmin 4:

Customers Table:

![alt text](Resources/CustomersTable.png)

Products Table:

![alt text](Resources/ProductsTable.png)

ReviewIdTable:

![alt text](Resources/ReviewIdTable.png)

VineTable:

![alt text](Resources/VineTable.png)



Overall, this assignment provided me a good exposure to BigData and ETL processes in general.


