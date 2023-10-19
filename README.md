# JDBC Database Connection and Data Retrieval Application

This application aims to connect to a MySQL database using Java JDBC and retrieve data from it. It provides database connection to access the relevant table and print this data to the screen.

## Application Components

1. The `DatabaseConnection` class manages creating a connection to the database and returning that connection.
2. The `EmployeeDataRetrieval` class is used to retrieve and print employee information from the database.

## Usage

- When the program starts, it attempts to create a connection to the database. If the connection is unsuccessful, the code falls back to using static data (from a text file).
- If the database connection is successful, data is retrieved from the relevant database table and printed to the screen.

This application provides an excellent example for understanding JDBC usage and basic database operations. The ability to fallback to static data sources when the database connection is unsuccessful is important for reliability.

**Screenshot:**

[Insert Screenshot](/img/ss.png)
