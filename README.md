# Flask-project
CREATE DATABASE USERS;
USE users;

CREATE TABLE users (
    id INT PRIMARY KEY,
    name VARCHAR(20) ,
    email VARCHAR(20) ,
    role VARCHAR(20) 
);

INSERT INTO users values(1,'aafreen','aaf@gmail.com','web developer');
INSERT INTO users values(2,'afreen','afreen@gmail.com','web developer');
INSERT INTO users values(3,'savitha','savi@gmail.com','application developer');
INSERT INTO users values(4,'sharmila','sharmila@gmail.com','web developer');
INSERT INTO users values(5,'afrose','afrose@gmail.com','accountant');
    
-- Query to retrieve all the users 
SELECT * FROM  users;

-- Query to retrieve a specific user 
SELECT * FROM users WHERE id = 2;
