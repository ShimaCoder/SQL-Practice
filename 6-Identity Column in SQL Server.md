[Training video](https://www.youtube.com/watch?v=aOkFE6NLGCQ&list=PL08903FB7ACA1C2FB&index=8)

## Identity Column in SQL Server (Command/DDL DATA DEFINATION LANGUAGE)

If a column is marked as an identity column, then the values for this column are automatically generated, when you insert a new row into the table. A god example of a identity column is ID column.

## To explicitly supply a value for identity column
1.	First turn on identity insert-SET Identity _Insert tableperson ON
2.	In the insert query specify the column list 
Insert into tableperson(PersonId,Name) values (2,’shima’)

Then if you want to get back to the default identity column setting that you just enter a name and it added in to the id column without providing the id you turn off the identity insert.

If you have deleted all the rows in a table,and you want to reset the identity column value,use DBCC CHECKIDENT command.
```
DBCC CHECKIDENT(‘tblPerson,RESEED,0)
```
