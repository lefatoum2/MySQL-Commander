# MySQL-Commander

![img1](https://www.denofgeek.com/wp-content/uploads/2020/05/demolition-man-sylvester-stallone-sandra-bullock-warner-bros.jpg?fit=1200%2C680)

https://blog.devart.com/mysql-command-line-client.html

C:\Program Files\MySQL\MySQL Server 8.0\bin

mysql -u root -p

## Creating User 

CREATE USER 'username' IDENTIFIED BY 'password';

GRANT SELECT ON *.* TO 'username';

GRANT ALL PRIVILEGES ON *.* TO 'username';

## Deleeting a user 

DROP USER 'username'; 

## Creating a database

CREATE DATABASE dbname; 

USE dbname;

## Deleting a database

DROP DATABASE dbname;


## Help

help or \h
