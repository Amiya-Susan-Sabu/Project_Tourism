# Project_Tourism
Training Mini Project-Group 9

Training Project build on Eclipse IDE for Enterprise Java Developers. Version: 2019-09 R (4.13.0) Build id: 20190917-1200 with jdk 1.8
Maven Project based on maven-archtype-webapp 1.0
mySQL 5.7.


Used Database sql query:

use tourism_project;
create table TourPackage(
id int primary key auto_increment,
name varchar(20),
fromLocation varchar(20),
toLocation varchar(20),
days int(3),
price Double
)ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;

create table tourists(
user varchar(10),
password varchar(10),
primary key(user)
);

insert into TourPackage values
	(1,'Chloe','Chicago','Las Vegas',5,5000.00),
	(2,'Ryan','Washington','New Orleans',10,25000.00),
	(3,'Zoey','Illinois','Nevada',7,10000.00),
	(4,'Zack','Palm Springs','Louisiana',7,15000.00),
	(5,'Emma','San Diego','Philadelphia',4,7000.00);
commit;

insert into tourists values
     ('Jim','Jim@2020'),
     ('Cathy','Cathy@123');
commit;



For Login:
use details from table tourists.
