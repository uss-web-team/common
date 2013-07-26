# SQL

...

## Exercise

Connect to the following URL:

```
jdbc:oracle:thin:@dev10db.it.utah.edu:1528:dev10
```

There is a table called `COUNTRY`.

```sql
-- Inspect the columns of this table.
desc country;
```

```sql
-- Retrieve all columns for all rows in country.
select * from country;
```

```sql
-- Retrieve all columns for all rows in country where the country begins with the letter 'A'.
select * from country where country_name like 'A%';
```
