# Learning SQL Through Doing

## Instructions-Query the Chinook Music Store Database

## Installing a local version of the Chinook Database
* We will be coding against the Chinook database.
* A sql script for installing can be downloaded from here. https://chinookdatabase.codeplex.com/
* Once you have downloaded the zip file. You will see several scripts.
* Open the one called "Chinook_SqlServer.sql"
* Open the file in a text editor. 
* Select and copy all of the text in the file.
* In Visual Studio open the "Sql Server Object Explorer Window"
* Right click on your server icon. It should be the same name as your computer.
* Choose "New Query"
* Paste the contents of "Chinook_SqlServer.sql" into the query window.
* Click the green arrow to the left of the window to run the sql.
* Once the code has executed successfully, refresh your server in the "Sql Server Object Explorer Window"
* You should now see the chinook database. 

For each of the following exercises, provide the appropriate query. Yes, even the ones that are expressed in the form of questions. Everything from class and the [Sqlite Documentation](http://www.sqlite.org/) is fair game. 

1. Provide a query showing Customers (just their full names, customer ID and country) who are not in the US.
1. Provide a query only showing the Customers from Brazil.
1. Provide a query showing the Invoices of customers who are from Brazil. The resultant table should show the customer's full name, Invoice ID, Date of the invoice and billing country.
1. Provide a query showing only the Employees who are Sales Agents.
1. Provide a query showing a unique list of billing countries from the Invoice table.
1. Provide a query that shows the invoices associated with each sales agent. The resultant table should include the Sales Agent's full name. 
1. Provide a query that shows the Invoice Total, Customer name, Country and Sale Agent name for all invoices and customers. 
1. How many Invoices were there in 2009 and 2011? What are the respective total sales for each of those years?(include both the answers and the queries used to find the answers)
1. Looking at the InvoiceLine table, provide a query that COUNTs the number of line items for Invoice ID 37.
1. Looking at the InvoiceLine table, provide a query that COUNTs the number of line items for each Invoice. HINT: [GROUP BY](http://www.sqlite.org/lang_select.html#resultset)
1. Provide a query that includes the track name with each invoice line item.
1. Provide a query that includes the purchased track name AND artist name with each invoice line item.
1. Provide a query that shows the # of invoices per country. HINT: [GROUP BY](http://www.sqlite.org/lang_select.html#resultset)
1. Provide a query that shows the total number of tracks in each playlist. The Playlist name should be include on the resulant table.
1. Provide a query that shows all the Tracks, but displays no IDs. The resultant table should include the Album name, Media type and Genre.
1. Provide a query that shows all Invoices but includes the # of invoice line items.
1. Provide a query that shows total sales made by each sales agent.
1. Which sales agent made the most in sales in 2009? HINT: [MAX](https://www.sqlite.org/lang_aggfunc.html#maxggunc)
1. Which sales agent made the most in sales over all?
1. Provide a query that shows the # of customers assigned to each sales agent.
1. Provide a query that shows the total sales per country. Which country's customers spent the most?
1. Provide a query that shows the most purchased track of 2013.
1. Provide a query that shows the top 5 most purchased tracks over all.
1. Provide a query that shows the top 3 best selling artists.
1. Provide a query that shows the most purchased Media Type.

