[training video](https://www.youtube.com/watch?v=oqrsfatxTYE&list=PL08903FB7ACA1C2FB&index=10)

**Unique Key Constrain** (Command/DDL DATA DEFINATION LANGUAGE)

We use UNIQUE constraint to enforce uniqueness of a column .i.e the column shouldn’t allow any duplicate values. We can add a unique constraint thru the designer or using a query.

Both primary key and unique key are used to enforce, the uniqueness of a column. So, when do you choose one over the other?
A table can have, only one primary key. If you want to enforce uniqueness on 2 or more columns, then we use unique key constrain.

What is the difference  between primary key constraint and unique key constrain?
1.	A table can have only one primary key, but more than one unique key
2.	Primary key does not allow null, where as unique key allows one null
