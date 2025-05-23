# Final-Lab-Task-5
- This portfolio showcases the application of SQL views, stored procedures, and functions to handle and manipulate database data. It includes tasks such as filtering data using views, updating information through procedures, and retrieving results using functions.

## Step by Step Process

1. **Initialize MySQL Workbench:**

   * Launch XAMPP and start the MySQL server.
   * Connect to the server via MySQL Workbench.
   * Run test queries using the `democodes.sql` script.

2. **Access the Inventory Database:**

   * Begin working with the `inventory.sql` file.

3. **Build SQL Views:**

   * Create a view to show vendor and product information for items with an in-date from 2002 onwards.
   * Make a view listing products priced between 100 and 150.
   * Create a view to calculate the total price (`on_hand * price`) for items sold by selected vendors.

4. **Develop a Stored Procedure:**

   * Write a procedure to change the vendor name from 'Bryson, Inc.' to 'Bryson and Co'.

5. **Write a Function:**

   * Create a function that accepts vendor code and state as inputs, returning product descriptions and prices that match.

6. **Run and Document Results:**

   * Execute all SQL commands and include screenshots of both the code and the output.



## Sample Screenshots and Results:

### 1. View for vendor info and products from 2002 onwards**
#### Code:
![Image]()
#### Output:
![Image]()

### 2. View for products priced between 100 and 150**

#### Code:
![Image]()
#### Output:
![Image]()

### 3. View to calculate total product price from selected vendors**

#### Code:
![Image]()
#### Output:
![Image]()
### 4. Stored procedure to update vendor name**

#### Code:
![Image]()

#### Output:
![Image]()
### 5. Function to filter products by vendor code and state**

#### Code:
![Image]()
#### Output:
![Image]()
