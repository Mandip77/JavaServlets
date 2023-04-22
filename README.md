# JavaServlets
This a simple course work project , web application for a budget management using Java via jetty servlets with freemaker and mysql database

I just made a simple school project application using Java and Jetty. This web application template demonstrates how to create and run servlets with the Apache FreeMarker Template engine via the embedded Jetty engine. Please follow the steps below to set up and run the project.

## Simple Java Servlets with Jetty Web Application Template
This repository contains a simple school project application created using the Java programming language. The application utilizes servlets and the Apache FreeMarker Template engine via the embedded Jetty engine.

Prerequisites
Before using the web application, please make sure to run the BudgetLoader and TransactionLoader classes to load the budget categories and transactions data into the database.

### To do this, follow these steps:

Make sure you have a valid category.csv file with budget categories in the project root directory.
Make sure you have a valid transactions.csv file with transactions data in the project root directory.
Run the BudgetLoader class in your IDE or using the command line. This will load the budget categories data from the CSV file into the database.
Run the TransactionLoader class in your IDE or using the command line. This will load the transactions data from the CSV file into the database.

#### Running the server
To run the server, execute the following command:
mvn jetty:run

With the server running, you can now access the web application through your browser.
