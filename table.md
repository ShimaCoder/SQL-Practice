https://www.youtube.com/watch?v=JLeaM8pK8dE&list=PL08903FB7ACA1C2FB&index=5
Part 3/ Video 4
Creating Tables/ Enforcing Primary key and foreign key constraints (Command/DDL DATA DEFINATION LANGUAGE)
Can create table graphicly look for it later 
Using syntax to create a table
Create Table TableName
(
ColumnName  DataType Null or Not   I want to be primary key,
ColumnName  DataType Null or Not   I want to be primary key
)

Create Table Gender
(
ID  int  Not Null  Primary key,
Gender Nvarchar(50) Not Null
)

Primary Key Column= is use to uniquely identify each record withing a table
Foreign Key Column= A foreign key in one table points to primary key in another table. The foreign key constraint(limitation) prevents invalid data from being inserted in to the foreign key column. The values that you enter into the foreign key column, had to be one of the values contained in the table it point to.in another word by adding foreign key relationship the reference for the column will be the data in the foreign key column so it will not accept any random data in the column that is not in the reference column or the foreign key column is.
