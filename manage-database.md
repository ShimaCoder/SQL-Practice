[Training Video](https://www.youtube.com/watch?v=TuxuHHacIWU&list=PL08903FB7ACA1C2FB&index=4)

## Creating, Altering, Dropping (Delete) a Database
Tages: Command/DDL (Data Definition Language)
A database is an object in sql server just like a table and...
To create a Database (object):

```
Create Database {DatabaseName};
```

When a Database is created. two main file will be Created with it:
* MDF File
* LDF (Log File) 

### Altering (Modifying)
Alter Database DatabaseName Name= NewDatabaseName
Note:	for altering we can also use Stored Procedure as well.

### Delete/Drop
```
Drope Database DatabaseName
```

Note: when a Database is Drop the MDF and LDF file will be deleted to.

Note: A data base in use can not be deleted you need to put the database to single_User mood and then drop the database With rollback immediate option will rollback all incomplete transaction and closes the connection to the database.

Note: system database cannot be dropped.
