## Vizualizing table relationships using Database Diagrams

If a Database diagram does not already exist, we can create a new one by right clicking 'Database Diagrams' and selecting 'New Database Diagram'
![](../zzImages/Pasted%20image%2020230916171422.png)

Then we can select the tables we want to see (all of them because why not) and hit 'Add' & 'Close'
*Tip*: zoom out if the database is large

Here's just one section of our database diagram:
![](../zzImages/Pasted%20image%2020230916171647.png)

	We can see that **ProductID** is a common primary key.

## Example Queries to answer questions

1. What is the most historical date on record that a business credit card was modified?
	May 31st, 2011
![](../zzImages/Pasted%20image%2020230916162653.png)

2. Compare the StockedQty with the SafetyQty to help determine if production needs increased for any products:
	We can see that the WorkOrder and Product tables contain columns we want to look at so we can join them and return the columns we're interested in:
![](../zzImages/Pasted%20image%2020230916174009.png)
![](../zzImages/Pasted%20image%2020230916174137.png)


