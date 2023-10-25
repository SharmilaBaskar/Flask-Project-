Objective: 
The objective of this assignment is to assess your skills and knowledge as a Software Engineer in the areas 
of Python Flask/Django, MySQL, and Git concepts. You will be required to complete a series of tasks that 
simulate real-world scenarios and demonstrate your understanding and proficiency in these technologies.

Task 2
Create a MySQL database with the name "users". 
 b. Design a table "users" with the following columns: 
 - id (int, primary key) 
 - name (varchar) 
 - email (varchar) 
 - role (varchar) 
 c. Write SQL queries to: 
 - Insert sample data into the "users" table. 
 - Retrieve all users from the "users" table. 
 - Retrieve a specific user by their ID.

 - CREATE DATABASE users;
 - USE formate;
 - CREATE TABLE users(
 -   id INT PRIMARY KEY,name VARCHAR(30),email VARCHAR(30),role(30));
 -   INSERT INTO formate(name,email,role)
 -   VALUES( 1,'sharmila','sharmila@gmail.com','user'),(2,'pavi','pavish@gmail.com','admin'),(3,'sathya','sathisharmi@gmail.com','user');

 -   SELECT*FROM users;
 -   SELECT *FROM users WHERE id= 3;
