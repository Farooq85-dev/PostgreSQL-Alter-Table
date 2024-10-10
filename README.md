# PostgreSQL-Alter-Table

## This repository is about we properly use Alter Table in PostgreSQL.

### `ALTER TABLE`

#### It is used to modify the properties of table. For example:-

#### There are some queries are used with alter table.

### 1) `ADD COLUMN`

#### It is used to add column in a existing table.

```
ALTER TABLE EMPLOYEES ADD COLUMN COUNTRY;
```

### With DATATYPE:-

```
ALTER TABLE EMPLOYEES ADD COLUMN COUNTRY SET DATATYPE VARCHAR(100);
```

### With NOT NULL:-

```
ALTER TABLE EMPLOYEES ADD COLUMN COUNTRY NOT NULL;
```

### With DEFALULT VALUE:-

```
ALTER TABLE EMPLOYEES ADD COLUMN COUNTRY DEFAULT 50;
```

### 2) `RENAME COLUMN`

#### It is used to rename column in a existing table.

```
RENAME COLUMN COUNTRY TO CCOUNTRY;
```

### 3) `DROP COLUMN`

#### It is used to drop column in a existing table.

```
ALTER TABLE EMPLOYEES DROP COLUMN;
```

### 4) `RENAME COLUMN`

#### It is used to rename table in a existing table.

```
RENAME TABLE EMPLOYEES TO EEPMLOYEES;
```
