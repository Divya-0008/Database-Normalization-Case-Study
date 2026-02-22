# Database-Normalization-Case-Study

This project demonstrates the concept of Database Normalization using MySQL Command Line Client.  
The case study converts unnormalized employee project data into First Normal Form (1NF), 
Second Normal Form (2NF), and Third Normal Form (3NF).

The project is implemented entirely using SQL commands executed through MySQL Command Line Client.


Objectives :-
- To understand the concept of normalization
- To remove data redundancy
- To improve data integrity
- To design a structured relational database



Tools Used :-
- MySQL Server
- MySQL Command Line Client
- SQL



Project Structure :-

1.Database Creation
Creating database here.
Contains redundant and repeating data.

2.First Normal Form (1NF)
- Ensures atomic values.
- Removes repeating groups.
- Each column contains a single value.

3.Second Normal Form (2NF)
- Removes partial dependency.
- Separates employee and project information into different tables.
- Introduces proper primary keys.

4.Third Normal Form (3NF)
- Removes transitive dependency.
- Separates manager information.
- Establishes relationships using foreign keys.


How to Execute :-
1.Install MySQL on your system.
2.Open MySQL Command Line Client from Start Menu.
3.Enter your MySQL root password to log in.
4.Create a new database for the project.
5.Select the created database.
6.Execute the SQL queries step-by-step to create tables and normalize the data.
7.Insert sample data into the unnormalized table.
8.Create normalized tables (1NF, 2NF, 3NF) as defined in the project.
9.Run SELECT queries to verify the final structure and relationships.
10.Use the SHOW TABLES command to confirm successful table creation.


Learning Outcomes
- Understanding of normalization concepts
- Removal of redundancy
- Dependency analysis
- Relational database design
- Practical SQL implementation



Author
Divya Subhash Chandra Tripathi   
SYIT – DBMS Mini Project  
Academic Year: 2025-2026
