# DWH
A Data Warehouse Implementation for Adventure Works Dataset

This project is a data warehouse implementation using teradata. The details for the project are as follows:

The data for all the subject areas (Sales, Production, Purchase & Person) was in the form of Excel Files (contact me if you want the data).

The implementation follows the below mentioned steps:

Step 1:
To kick start, we need to load the data as it is in our data warehouse. This is done by fast load scripts with .fld extension. This layer is termed as Staging Layer

Step 2:
Now comes the foundation layer. In this layer we have two sub-layers, Load Ready (LDR) and Core. Both the sub-layers add further details to the data and are implemented so that the 
3rd normal form is acheived. Both the layers are implemented using Bteq scripts

Step 3:
Finally comes access layer. In this layer, Fact tables are implemented as per the business questions using sql.
