Relational Model  

![image](https://github.com/user-attachments/assets/e668384b-e78b-42a0-afac-946b0aafc544)

DB Creation Query:

-- create database RiwiAcademyDB;
-- use RiwiAcademyDB;

-- create table Student (
-- 	id int primary key auto_increment,
--     name varchar (125) not null,
--     email varchar(125) not null unique,
--     state boolean not null
-- );

-- create table Course (
-- 	id int primary key auto_increment,
-- 	name varchar(125) not null unique,
--     description varchar(155) not null
-- );

-- create table Subscription (
-- 	id int primary key auto_increment,
--     student_id int not null,
--     course_id int not null,
--     foreign key (student_id) references Student(id),
--     foreign key (course_id) references Course(id)
-- );

-- create table Grade (
-- 	id int primary key auto_increment,
--     value int not null,
--     subscription_id int not null,
--     foreign key (subscription_id) references Subscription(id) on delete cascade
-- );

-- alter table Grade add value double not null;


Repository URL: https://github.com/AarFeE/Java-Filter
