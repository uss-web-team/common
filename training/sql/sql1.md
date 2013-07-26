# SQL

## Reading

For starters, please read:
* [Queries](https://en.wikipedia.org/wiki/SQL#Queries)
* [Manipulation](https://en.wikipedia.org/wiki/SQL#Data_manipulation)

## Bookmarks

* [Oracle DB SQL Reference](http://docs.oracle.com/cd/B19306_01/server.102/b14200/toc.htm)
* [SQLPlus Command Reference](http://docs.oracle.com/cd/B19306_01/server.102/b14357/ch12.htm#sthref1725)

## Exercise

Connect to the following URL (ask a coworker for login credentials):

```
jdbc:oracle:thin:@dev10db.it.utah.edu:1528:dev10
```

### Basic statements

There is a table called `COUNTRY` in this database.

The [desc](http://docs.oracle.com/cd/B19306_01/server.102/b14357/ch12019.htm) statement.
```sql
-- Inspect the columns of this table.
desc country;
```

The [select](http://docs.oracle.com/cd/B19306_01/server.102/b14200/statements_10002.htm#i2065646) statement.
```sql
-- Retrieve all columns for all rows in country.
select * from country;
```

```sql
-- Retrieve all columns for all rows in country where the country begins with the letter 'A'.
select * from country where country_name like 'A%';
```

Please write a query for all countries that end with 'stan', such as Turkmenistan;

Please write a query for all countries that call themselves a 'Republic', and sort the results from Z to A.

Please write a query for all countries that either begin with a vowel ('A', 'E', 'I', 'O', 'U') **and** end in 'ia', such as Albania.

### Data Manipulation

insert

update

### unions, joins, ...
