# Task-4
SQL Server(Extraction,mapping,joins)

Data Loading and Extraction (SQL Server)

Tasks:
Load all provided datasets into SQL Server.
Extract Customers and Orders datasets separately using Python.
Perform necessary data joins to create a Unified Customer View that combines:
Customer Profiles
Order Information
All transformations listed below.
Load the Unified Customer View back into SQL Server for further analysis and reporting.
🔄 Data Transformation Requirements
1. Name Processing
Task:
Split the Name column into two separate fields:
First Name
Last Name
Use the space as a separator for splitting.
Additional Processing:
Remove common prefixes:
Examples: Mr., Mrs., Miss, Dr.
Remove common suffixes:
Examples: Jr., Sr., II, III
2. Country Code Extraction and Mobile Number Enrichment
Task:
Extract the country code from the Address field.
Enrichment:
Map the extracted country code to its respective international phone dialing code.
Prepend this dialing code to the customer's Mobile Number to form a complete, internationally formatted phone number.
3. Customer Classification
Task:
Add a new column named Customer_Tier based on the following mappings:
Tier	
Mapping Value

Gold	2
Silver	1
Bronze	0
 
 
 
