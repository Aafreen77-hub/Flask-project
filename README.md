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
INSERT INTO users values(2,'aafreen','aaf@gmail.com','web developer');
INSERT INTO users values(3,'aafreen','aaf@gmail.com','web developer');
INSERT INTO users values(4,'aafreen','aaf@gmail.com','web developer');
INSERT INTO users values(5,'aafreen','aaf@gmail.com','web developer');
    
-- Query to retrieve all the users 
SELECT * FROM  users;

-- Query to retrieve a specific user 
SELECT * FROM users WHERE id = 2;
