# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```

### OUTPUT:

![image](https://github.com/22008539/G2_DBMS/assets/118707617/d4078461-29d3-4714-aa2b-d859b4552fa6)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![image](https://github.com/22008539/G2_DBMS/assets/118707617/2c22e52a-f697-4647-8c27-19b5dbb87d15)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```
### OUTPUT:
![image](https://github.com/22008539/G2_DBMS/assets/118707617/d0c90400-b82a-4d48-898f-1d18b60f2f8a)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```

### OUTPUT:

![image](https://github.com/22008539/G2_DBMS/assets/118707617/a7cf6059-f7e7-4b7f-9db9-8e45b0246324)


### 5) Rename the student table to mystudent

### SQL QUERY: 

```
alter table student rename to mystudent;
```
### OUTPUT:
![image](https://github.com/22008539/G2_DBMS/assets/118707617/9d838847-3a92-4ec4-a2e6-a98d06085ad0)


### RESULT:

To create a student database and execute DDL queries using SQL is executed successfully.
