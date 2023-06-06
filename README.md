# creating_class_php

## Create new database user
.\mysql.exe -u root
grant all privileges on *.* to "base_name"@"localhost" identified by "some_password";
exit
.\mysql -u base_name -p
password

## Create database
create database exercise;

## Create table
create table todos (
id int auto_increment primary key,
title varchar(100) not null, 
done int(1) not null    
);

show databases; 

insert into todos values (null,"Learn PHP",0);
insert into todos values (null,"Learn JS",0);
insert into todos values (null,"Learn SQL",0);

select * from todos;

