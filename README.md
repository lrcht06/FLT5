# Finals Lab Task 5: Using SQL Views, Stored Procedures, and Functions
This portfolio demonstrates the application of SQL **Views**, **Stored Procedures**, and **Stored Functions** in managing and processing data from a relational database. The task builds upon a predefined inventory system structure and showcases how SQL abstraction can be used for modular and efficient data access.

---

## STEP BY STEP PROCESS

### STEP 1. Launch MySQL Workbench or phpMyAdmin and start XAMPP to activate MySQL.

### STEP 2. Open MySQL Workbench or phpMyAdmin and import the `inventory.sql` file to initialize the tables and data.

### STEP 3. Create and select the working database:
- #### Create a database named `inventoryDB`
- #### Use the database created

### STEP 4. Import the provided SQL structure (inventory.sql) into `inventoryDB` to load the necessary tables and sample data.

### STEP 5. Perform the following tasks using SQL Views, a Stored Procedure, and a Function:

- #### Task 1 – Create a VIEW that displays vendor\_code, vendor\_name, product\_description, and p\_indate for all products from 2002 onwards
  - Use `CREATE VIEW` to show records filtered by `p_indate >= '2002-01-01'`.
    
- #### Task 2 – Create a VIEW for products priced between 100 and 150
  - Use `WHERE` with `BETWEEN` in the view definition to show the price range.
    
- #### Task 3 – Create a VIEW that calculates the total price (p\_onhand × p\_price) of all products sold by vendors with codes: 21344, 23119, and 24288
  - Include a computed column in the view and filter using `IN()`.

- #### Task 4 – Create a STORED PROCEDURE that updates vendor name from 'Bryson, Inc.' to 'Bryson and Co'
  - Use `UPDATE` within a procedure that accepts a single parameter.

- #### Task 5 – Create a FUNCTION that takes v\_code and v\_state as parameters and returns matching product descriptions and prices
  - Use `JOIN` inside a function with parameters passed for filtering.

---

## Query Statements (Screenshots)
- ### Task 1
  ![screenshot](images/FLT5\(T1\).png)

- ### Task 2 
  ![screenshot](images/FLT5\(T2\).png)

- ### Task 3 
  ![screenshot](images/FLT5\(T3\).png)

- ### Task 4 
  ![screenshot](images/FLT5\(T4\).png)

- ### Task 5 
  ![screenshot](images/FLT5\(T5\).png)

---

## Table Structures (Screenshots)
- ### Table 1
  ![screenshot](images/FLT5\(tbl1\).png)

- ### Table 2
  ![screenshot](images/FLT5\(tbl2\).png)

- ### Table 3
  ![screenshot](images/FLT5\(tbl3\).png)

- ### Table 4
  ![screenshot](images/FLT5\(tbl4\).png)

- ### Table 5
  ![screenshot](images/FLT5\(tbl5\).png)

---

## SQL Copy (File)
> 📂
[L.E.Turla (Finals Lab Task 5 Code)](./files/L.E.%20Turla%20(FLT5_Code).sql)

---
