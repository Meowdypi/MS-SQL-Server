## Vizualizing table relationships using Database Diagrams

If a Database diagram does not already exist, we can create a new one by right clicking 'Database Diagrams' and selecting 'New Database Diagram'


![image](https://github.com/Meowdypi/MS-SQL-Server/assets/122643833/99b2801a-4d94-4a93-adf0-044efd10b6dc)


Then we can select the tables we want to see (all of them because why not) and hit 'Add' & 'Close'
*Tip*: zoom out if the database is large

Here's just one section of our database diagram:

![image](https://github.com/Meowdypi/MS-SQL-Server/assets/122643833/64a75cd8-9fcb-48b3-9139-333a6f55a201)


	We can see that **ProductID** is a common primary key.

## Example Queries to answer questions

1. What is the most historical date on record that a business credit card was modified?
	May 31st, 2011

![image](https://github.com/Meowdypi/MS-SQL-Server/assets/122643833/a7e42001-6955-4c11-b22a-7c1d25717f72)


3. Compare the StockedQty with the SafetyQty to help determine if production needs increased for any products:
	We can see that the WorkOrder and Product tables contain columns we want to look at so we can join them and return the columns we're interested in:

![image](https://github.com/Meowdypi/MS-SQL-Server/assets/122643833/479fb2f3-ca92-408a-a04d-8d3f51567c14)
![image](https://github.com/Meowdypi/MS-SQL-Server/assets/122643833/55752ac2-9a50-4679-8333-9a8c422b0e51)



