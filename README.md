# Airline-Managament-System
An airline management system is a software application that helps manage various operations and processes involved in an airline company. This system has been developed using Java as the programming language and MySQL as the database management system. The front-end interface has been built using Java swings.

Requirements
Java Development Kit (JDK) version 8 or later
MySQL Server version 5.7 or later
Installation
Install Java Development Kit (JDK) and MySQL Server if you don't have them already installed on your machine.

Clone the repository:

bash
Copy code
git clone https://github.com/karthiktelkar/Airline-Managament-System.git
Import the database file (airline_management.sql) into MySQL. This can be done using the following command in the MySQL terminal:
shell
Copy code
mysql> source [path-to-sql-file]/airline_management.sql;
Open the project in an Integrated Development Environment (IDE) such as Eclipse or IntelliJ.

Update the database credentials in the file named DbConnection.java located in the src/com/ams/util package. The default credentials are as follows:

java
Copy code
private static final String URL = "jdbc:mysql://localhost:3306/airline_management";
private static final String USER = "root";
private static final String PASSWORD = "";
Run the project as a Java application.
Features
Flight management

Add new flights
View flight details
Update flight details
Delete flights
Passenger management

Add new passengers
View passenger details
Update passenger details
Delete passengers
Ticket booking

Book a ticket
Cancel a ticket
View ticket details
User management

Add new users
View user details
Update user details
Delete users
Documentation
The source code is thoroughly commented and the class and method names are descriptive, making it easy to understand the code.

Contributing
Fork the repository
Create a branch for your feature (git checkout -b my-feature)
Commit your changes (git commit -am 'Add some feature')
Push to the branch (git push origin my-feature)
Create a new Pull Request
