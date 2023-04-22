# JavaServlets

# Jetty Web Application Template

This directory contains a template for creating and running servlets
and the Apache FreeMarker Template engine via the embedded Jetty engine.

## Prerequisites

Before using the web application, please make sure to run the `BudgetLoader` and `TransactionLoader` classes to load the budget categories and transactions data into the database.

To do this, follow these steps:

1. Make sure you have a valid `category.csv` file with budget categories in the project root directory.
2. Make sure you have a valid `transactions.csv` file with transactions data in the project root directory.
3. Run the `BudgetLoader` class in your IDE or using the command line. This will load the budget categories data from the CSV file into the database.
4. Run the `TransactionLoader` class in your IDE or using the command line. This will load the transactions data from the CSV file into the database.

## Running the server

To run the server type command:
mvn jetty:run
