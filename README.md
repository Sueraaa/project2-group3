# Project 02 - Group 03

## Introduction

In the ETL (Extract, Transform, Load) mini project, we will embark on an exciting journey to build an ETL pipeline using Python, Pandas, and various data manipulation techniques. The goal of this project is to gain hands-on experience in data extraction, transformation, and loading processes, which are fundamental in real-world data engineering projects.

Throughout this project, we will collaborate with our team to extract data from these given sources, transform it into a structured format suitable for analysis, and finally load the transformed data into a PostgreSQL database. We leverage Python libraries such as Pandas for data manipulation, and we have used Python dictionary methods to efficiently extract and transform the data.

As part of the ETL process, we have created four CSV files containing the transformed data. These CSV files will serve as the basis for creating an Entity-Relationship Diagram (ERD) and designing a table schema for the PostgreSQL database. This project will provide us a comprehensive understanding of the ETL process, from data extraction to database integration, and to gain valuable skills for handling real-world data engineering challenges.


## Resources

The group used the following resources throughout the development of this project:

- VS Code
- PostgreSQL
- Microsoft Excel
- [Quick Database Diagrams](https://www.quickdatabasediagrams.com/) - to build the ERD Diagram

## Data Importing Process 

* Importing campaign table into into crowdfunding_db_schema.sql,

![Import campaign table](Resources/SQL%20Screenshots/Import%20campaign%20table.png)

* Importing category table into into crowdfunding_db_schema.sql,

![Import category table](Resources/SQL%20Screenshots/Import%20category%20table.png)

* Importing contacts table into into crowdfunding_db_schema.sql,

 ![Import contacts table](Resources/SQL%20Screenshots/Import%20contacts%20table.png)

* Importing sub-category table into into crowdfunding_db_schema.sql,

![Import sub-category table](Resources/SQL%20Screenshots/Import%20subcategory%20table.png)

## Selected Queries from the Database

* The data from campaign table is displayed using a SELECT * statement,

![Select query campaign](Resources/SQL%20Screenshots/Select%20query%20campaign.png)

* The data from category table is displayed using a SELECT * statement,

![Select query category](Resources/SQL%20Screenshots/Select%20query%20category.png)

* The data from contacts table is displayed using a SELECT * statement,

![Select query contacts](Resources/SQL%20Screenshots/Select%20query%20contacts.png)

* The data from subcategory table is displayed using a SELECT * statement,

![Select query subcategory](Resources/SQL%20Screenshots/Select%20query%20subcategory.png)


## ERD Table 

The relationships between the entities are:
* The foreign key in the Campaign table (contact_id) references the primary key in the Contacts table.
* Category and subcategory connect to campaign through category_id & subcategory_id. 

![ERD Table](Resources/SQL%20Screenshots/ERD%20Diagram.png)