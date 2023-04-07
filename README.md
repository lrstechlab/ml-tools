# ml-tools
install python plugin
create a python project
brew install pandas
brew install mysql-connector-python
**************MySQLDB setup*********
1. Please follow link to Download mySQL from below link- http://dev.mysql.com/downloads/ Mysql server- https://dev.mysql.com/downloads/mysql/ 
2. MySql workbench- https://dev.mysql.com/downloads/workbench/

3. Create Database-
	create database tipicoCar;

4. create Table. first point to database you want to use and then create table

  use tipicoCar;
  create table activeJobs(JobTitle varchar(300), Department varchar(300), Location varchar(30));
  
  alter table activeJobs add primary key (JobTitle,Department,Location)
  
  check the details of your Table use tipicoCar; describe activeJobs;

