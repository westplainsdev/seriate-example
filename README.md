# seriate-example
Using The seriate NPM package to connect to a Microsoft SQL Express database version of the classic Northwind database. 

## Getting started. ##

Run npm install to get the seriate package. 

[Download][1] and run the Northwind database script.

Make sure your SQL Express database server is using the mix mode type of login. 

I found that it helped that the sql user has dbo.owner permissions and has full control of the database.

## Additional Resources##

[Blog Entry][2] going into a little more detail about the application and expanding upon it. 

[1]: https://northwinddatabase.codeplex.com/releases/view/71634
[2]: https://keyholesoftware.com/2016/04/04/seriate-the-glue-between-sql-server-and-node-js/
