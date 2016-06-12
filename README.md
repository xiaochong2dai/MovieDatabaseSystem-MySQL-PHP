# Goal
• Built a movie-database system with a user-friendly web interface supported by MySQL.<br>
• Wrote PHP pages that execute queries to find the requested info and render pages to users.

# Data 
Data is in the 'data' folder.

# Description of Our Dataset and Table Schema
Please see 'DescriptionOfOurDatasetAndTableSchema.pdf'.

# Loading and Querying the Dataset
• SQL script named 'create.sql' creates all tables above.<br>
• Create a databases 'MovieDatabase'.<br>
```
CREATE DATABASE MovieDatabase;
```
<br>
• Create the tables in the CS143 database, using a command like:<br>
```
mysql -u root -p MovieDatabase < create.sql 
```
(root is the username, and it will hint for password) <br>
• Create a MySQL script, named 'load.sql', that loads all our provided data into the created tables. <br>
```
mysql -u root -p MovieDatabase < load.sql 
```

# Building a Web Query Interface
Create a php page that allows users to type in a SQL SELECT statement in a text input box and submit the query through a Web browser. <br>
I first change working directory to where 'query.php' locates, then I started local server with the below command in MacBook terminal:
```
php -S localhost:8000/
```
Then at browser, I input the url: 
```
localhost:8000/query.php
```

# Web interfaces to find the requested info and render pages to users.
```
localhost:8000/php/*.php  
```
(I put all the php files in a folder 'php')
