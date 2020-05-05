# SQLite

### 

**How to start/connect:**

```
sqlite3
```



**How to exit:**

```
.exit
```



**Open SQLite with a .db file**

```
sqlite3
sqlite3> .open tablename.db
```



**How to view table(s):**

```
.table
```





## Create

**How to create a table:**

```
CREATE TABLE name ();
```





## Select / READ

**Select all data in a table:**

```
SELECT * FROM name;
```



**Select certain columns:**

```
SELECT arg1,arg2 FROM table_name;
```



**<code>WHERE</code> optional clause for SELECT for conditional logic**

```
SELECT arg1, arg2
FROM tablename
WHERE arg1 <= X 
```



**Multiple conditions**

```
SELECT arg1, arg2
FROM tablename
WHERE attribute <= X AND name = 'name';
```





## Update



**Insert row into a table**

```
INSERT INTO tablename (arg1, arg2) VALUES (arg1, arg2);
```





**Update a specific column within a row with <code>WHERE</code>**

```
UPDATE tablename
SET attribute='new'
WHERE id=user_id;
```





## Delete

**Delete row(s)**

```
DELETE FROM tablename
WHERE attribute = some_condition;
```



**Drop entire table**

```
DROP Table
```





# FlaskSQLAlchemy





