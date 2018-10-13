# University_Management_System
For Run this Code You Require This Table And Database In Mysql...

Following are queries....

CREATE DATABASE university;
CREATE TABLE course(id VARCHAR(20),NAME VARCHAR(20),credit INT);
CREATE TABLE course_reg(s_id INT,dept VARCHAR(15),college VARCHAR(40),NAME VARCHAR(40),semister VARCHAR(10),YEAR INT,c_name VARCHAR(25),c_id VARCHAR(10)); 
CREATE TABLE result(s_id INT,dept VARCHAR(20),college VARCHAR(40),s_name VARCHAR(40),semister VARCHAR(10),YEAR INT,c_name VARCHAR(20),c_id VARCHAR(15),credit INT ,marks INT);
CREATE TABLE stud(id INT,NAME VARCHAR(40),college VARCHAR(40),dept VARCHAR(15),email VARCHAR(40),mono INT,gender VARCHAR(5),padd VARCHAR(100));
CREATE TABLE teacher(id INT,NAME VARCHAR(40),college VARCHAR(40),dept VARCHAR(15),des VARCHAR(30),email VARCHAR(40),mono INT,gender VARCHAR(5),padd VARCHAR(100))
CREATE TABLE stud_login(username VARCHAR(30),PASSWORD VARCHAR(20));
CREATE TABLE teacher_login(username VARCHAR(30),PASSWORD VARCHAR(20));
CREATE TABLE admin(username VARCHAR(30),PASSWORD VARCHAR(20));
INSERT INTO admin VALUES("admin","admin");
SELECT * FROM stud;
