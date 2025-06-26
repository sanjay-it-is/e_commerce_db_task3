# Task 3: E-commerce Database Basic SELECT Queries

This repository contains an SQL script (`e_commerce_db_task3.sql`) focused on fundamental data retrieval operations using `SELECT` statements within your E-commerce PostgreSQL database.

##  Objective

The main goal of this task is to gain a clear understanding and hands-on experience in retrieving data effectively from one or more tables by:
* Using `SELECT *` to retrieve all columns and `SELECT column1, column2` for specific columns.
* Applying filtering conditions with `WHERE` clauses, including `AND`, `OR`, `LIKE`, `BETWEEN`, `IN`, `IS NULL`.
* Sorting query results using `ORDER BY` in ascending (`ASC`) or descending (`DESC`) order, including sorting by multiple columns.
* Limiting the number of rows returned using the `LIMIT` clause.


##  Contents

* `e_commerce_db_task3.sql`: The primary SQL script containing various `SELECT` query examples.

##  Key Demonstrations

The script illustrates a range of basic `SELECT` queries, including:

* **Column Selection**: Examples of fetching all columns (`*`) versus a subset of specific columns.
* **Filtering Data (`WHERE`)**:
    * Simple equality and comparison operators (`=`, `>`, `<`).
    * Combining conditions with `AND` and `OR`.
    * Pattern matching using `LIKE`.
    * Range selection with `BETWEEN`.
    * List matching with `IN`.
    * Checking for presence or absence of values with `IS NULL`.
* **Sorting Results (`ORDER BY`)**: Arranging data in ascending or descending order based on one or multiple columns.
* **Limiting Results (`LIMIT`)**: Fetching a specific number of top or bottom records after sorting.
 

##  How to Use

1.  **Prerequisite**: Ensure your E-commerce database schema and sample data are already set up and populated in your PostgreSQL environment. You should have completed
2.  [Task 1 - Database Setup and Schema Design](https://github.com/sanjay-it-is/e-commerce-db) and
3.   [Task 2 - Data Insertion and Handling Nulls](https://github.com/sanjay-it-is/e-commerce-db_task2).
4.  **Connect to your Database**: Open your preferred PostgreSQL client (e.g., `psql` command line, pgAdmin, DBeaver).
5.  **Execute the Script**: You can run the `e_commerce_db_task3.sql` file against your `e_commerce_db` database.

    ```bash
    -- Example using psql:
    psql -U your_username -d e_commerce_db -f e_commerce_db_task3.sql
    ```
    Alternatively, you can copy and paste individual queries or the entire script into your client and execute them to see the results.

## 📝 Outcome

By working through this script, you will gain a clear understanding of how to effectively retrieve, filter, sort, and limit data from a relational database using standard SQL `SELECT` queries, forming the cornerstone of data analysis and application development.
