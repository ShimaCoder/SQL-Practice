Select specific or all columns
Select * from tableperson
or 
SEKECT [ID]
,[NAME]
,[Email]
,[GenderID]
,[Age]
,[City]
FROM [Sample].[dbo].[tablePerson]
GO

distinct rows (diffrent rows)
Select DISTINCT City from tableperson
the resoult will be the citys but will not repeat a city that was used for diffrent rows a city can be repeated it will avoid repeating it and will
just tell us the name of the citys no matter how many time is used in a table

Note: if distinct is used across two columns is distinct between the two (city and naeme) column so you might get repeated city but because of different name they are not considered reapetd its distinct between the name its a cross between the two column.


filtering with where clause
by using where clause we specifiey our condition in it.
 we can use operators and wild cards in this
 = equal to
 <> != not equal to
 > grater than
 >= grater than or equal to
 < less than
 <= less than or equal to
 IN specifiey a list of values
 BETWEEN specity a range
 LIKE specify a pattern
 NOT not in a list, range etc
 % wpecifies zero or more characters
 - specifies exactly one character
 [] any character with in the brackets
 [^] Not any character with in the brackets


wild cards in sql server

joining multiple conditions using AND and OR operators

sorting rows using order by 

selecting top n or top n percentage of rows
