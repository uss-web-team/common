# SQL

## Bookmarks

* [Oracle DB SQL Reference(http://docs.oracle.com/cd/B19306_01/server.102/b14200/toc.htm)

## Exercise

Connect to the following URL:

```
jdbc:oracle:thin:@dev10db.it.utah.edu:1528:dev10
```

There is a table called `COUNTRY`.

### Basic statements

The [desc]() statement.
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
