<h2>DATABASE</h2>

A database is a structured collection of data that is organised so that it can be easily accessed ,managed and updated it is typically stored and managed using specialised software called a database management system dbms.
<br>
For example Mysql, SQLlite

<h2>DBMS</h2>
DBMS stands for database management system .It is software that allows users to interact with the database.Dbms's are designed to manage large volumes of data efficiently and provide mechanisms for storing, retrieving ,updating and managing that data.
<br>
example are Oracle

<h2>SQL</h2>
SQN structured query language it's I standardised language for managing relational databases you can use it to interact with various database systems to insert update delete and retrieve data 
<h2>MYSQL</h2>
mysql an open source rdbms that uses sql.Think of it as a database with Sql as its excess language ,other examples include Microsoft Sql Server and Oracle database.
<h2>Analogy</h2> 
Imagine Sql as a common language you can use to communicate with different librarians(relational database management systems) my sql would be a specific library with its own collection(database) that you can access and manage using sql commands.
<br><br>

![alt text](./images/image.png)<br>
![alt text](./images/image-1.png)<br>
![alt text](./images/image-2.png)<br>
![alt text](./images/image-3.png)<br>
![alt text](./images/image-4.png)<br>
![alt text](./images/image-5.png)<br>

<h2>TABLE</H2>
Table is a collection of data organised in rows and columns, they were used to store n organise data in a structured format making it easier to search, retrieve and manipulate the data.
<h2>DATA TYPES</H2>
DataType tells the database what kind of information can be stored in a particular column, for example a column with a data type of "integer" can only store whole numbers, while a column with the data type of "text" can be stored letters numbers and other characters.<br><br>

![alt text](image.png)<br>
![alt text](image-1.png)<br>
![alt text](image-2.png)<br>
![alt text](image-3.png)<br>
![alt text](image-5.png)<br>
![alt text](image-4.png)<br>
![alt text](image-6.png)<br>
![alt text](image-7.png)<br>
![alt text](image-8.png)<br>

<br><br>

<h2>How can we insert data in particular tables in a specific columns :</h2>

![alt text](image-9.png)
![alt text](image-10.png)

<br><br>

<h2>Fetching data</h2>

![alt text](image-11.png)
![alt text](image-12.png)

![alt text](image-13.png)
![alt text](image-14.png)
![alt text](image-15.png)
![alt text](image-16.png)
![alt text](image-17.png)
![alt text](image-18.png)
![alt text](image-19.png)
![alt text](image-20.png)
![alt text](image-21.png)
![alt text](image-22.png)
![alt text](image-23.png)
![alt text](image-24.png)
![alt text](image-25.png)
 ![alt text](image-26.png)
 ![alt text](image-27.png)
 ![alt text](image-28.png)
 ![alt text](image-29.png)
 ![alt text](image-30.png)
 ![alt text](image-31.png)
 ![alt text](image-32.png)
 ![alt text](image-34.png)
 ![alt text](image-35.png)
 ![alt text](image-36.png)
 ![alt text](image-37.png)
 ![alt text](image-38.png)
 ![alt text](image-39.png)
 ![alt text](image-40.png)
 ![alt text](image-41.png)
 ![alt text](image-42.png)
 <br><br>

 ![alt text](image-43.png)
 ![alt text](image-44.png)
 <br><br>

 ![alt text](image-45.png)
 ![alt text](image-46.png)
 ![alt text](image-47.png)
 ![alt text](image-48.png)
 ![alt text](image-49.png)
 ![alt text](image-50.png)
 ![alt text](image-51.png)
 ![alt text](image-52.png)
 <br><br>

 ![alt text](image-53.png)
 ![alt text](image-54.png)
 ![alt text](image-55.png)
 ![alt text](image-56.png)
 ![alt text](image-57.png)
 ![alt text](image-58.png)
 
------CROSS JOIN

--A cross join is the type of join operation that combines each row from one table with every row from another table ,it essentially creates a new result set containing all possible combinations of rows from the joined tables.

select * from engineer cross join tasks 

--or another syntax ->

select * from employee,tasks

-----INNER JOIN

--An inner join selects records that have matching values in both tables.

select * from engineer e
inner join tasks t on e.id=t.id


---LEFT JOIN
----------------A left join returns all records from the left table (engineer) and the match records from the right table (tasks),
---------------- if there's no match the result is null from the right side

select * from engineer e
left join tasks t on e.id=t.id      

--RIGHT JOIN
-----------------A right joint returns all records from the right table (tasks),and the matched records from the left table(engineer)....If there's no match,the result is null from the left side.

select * from engineer e
right join tasks t on e.id=t.id


<br>


![alt text](image-59.png)
![alt text](image-60.png)


![alt text](image-61.png)