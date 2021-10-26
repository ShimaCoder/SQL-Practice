[Training Video](https://www.youtube.com/watch?v=n1iwngG_zNY&list=PL08903FB7ACA1C2FB&index=9)

## Retrieving Identity Column Values (Command/DDL DATA DEFINATION LANGUAGE)

There are several ways in sql server to retrieve the last identity value that is generated. The most common way is to use SCOPE_IDENTITY() built in function.

**NOTE=** you can also use @@IDENTITY and IDENT_CURRENT(‘TalbeName’)

### Difference: 

**SCOPE_IDENTITY() –** same session and the same scope.

**@@IDENTITY-** Same session and across any scope.

**IDENT_CURRENT(‘TalbeName’)-** Specific table across any session and any scope.

