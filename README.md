Airline Management System
The Airline Management System is a Java-based desktop application developed using Java Swing for the front-end and MySQL for the back-end database. This project is designed to simulate and manage basic functionalities of an airline reservation system, such as customer management, ticket booking, flight scheduling, and user authentication.

Project Structure and Technology Stack
Language Used: Java
GUI Library: Java Swing]
Database: MySQL
Database Connectivity: JDBC
IDE Used: NetBeans
Build Tool: Apache Ant (default in NetBeans)
JDK Version: Java SE 8 or later

Features
Admin login functionality with authentication
Add and manage customer details
Flight creation and management
Ticket booking and ticket cancellation
Search functionality for flights and customers
Real-time data update with MySQL backend

How to Run the Project:
Clone the Repository
Download or clone the repository to your local system.

Setup Database:
Open MySQL or any SQL client and execute the following commands:

sql:
CREATE DATABASE airlinemanagementsystem;
USE airlinemanagementsystem;

CREATE TABLE login (
    username VARCHAR(20),
    password VARCHAR(20)
);

INSERT INTO login VALUES ('admin', 'admin');
Add MySQL Connector
Download the MySQL Connector/J and add the JAR file to the project libraries in NetBeans:

Right-click on the project

Choose Properties

Go to Libraries → Compile

Click “Add JAR/Folder” and select the MySQL Connector JAR

Build the Project

Right-click the project in NetBeans

Click “Clean and Build”
