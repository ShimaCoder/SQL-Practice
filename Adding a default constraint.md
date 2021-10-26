[Training Video](https://www.youtube.com/watch?v=dwSqHhMl32Y&list=PL08903FB7ACA1C2FB&index=6)

## Adding a default constraint (Command/DDL DATA DEFINATION LANGUAGE)

A column default can be specified using default constraint. The DEFAULT constraint is used to insert a default value into a column. The default value will be added to all new records, if no other value is specified, including NULL. In another word
So as we know constraint is to set a rule now we are going to have a default rule in a table that if we don’t provide a value for a column it will fill the gab with a default value that we set by using default constraint.

### Altering an existing column to add a default constraint:
```
ALTER TABLE {TABLE_NAME}
ADD CONSTRAINT {CONSTRAIN_NAME}
DEFAULT {DEFAULT_VALUE} FOR {EXISTING_COLUMN_NAME}
```
### Adding a new column, with default value, to an existing table:
```
ALTER TABLE {TABLE_NAME}
ADD {COLUMN_NAME} {DATA_TYPE} {NULL I NOT NULL}
CONSTRAINT {CONSTRAINT_NAME} DEFAULT {DEFAULT_VALUE}
```
### Dropping a constraint:
ALTER TABLE {TABLE_NAME}
DROP CONSTRAINT {CONSTRAINT_NAME}
```
