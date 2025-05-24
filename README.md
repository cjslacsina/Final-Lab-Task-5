# Finals-Lab-Task-5
- This portfolio demonstrates the use of SQL views, stored procedures, and functions to manage and process database data. It covers tasks such as filtering data with views, updating records via procedures, and retrieving results through functions.

## Step by Step Process

1. **Set Up MySQL Workbench:**

   * Start XAMPP and activate the MySQL server.
   * Connect to the server using MySQL Workbench.
   * Execute test queries with the `democodes.sql` script.

2. **Access the Inventory Database:**

   * Open and work with the `inventory.sql` file.

3. **Create SQL Views:**

   * Design a view to display vendor and product details for items with an in-date from 2002 onwards.
   * Develop a view that lists products priced between 100 and 150.
   * Create a view that calculates the total price (`on_hand * price`) for items sold by specific vendors.

4. **Create a Stored Procedure:**

   * Develop a procedure to update the vendor name from 'Bryson, Inc.' to 'Bryson and Co'.

5. **Write a Function:**

   * Build a function that accepts vendor code and state as inputs, returning the product descriptions and prices that match.

6. **Execute and Document Results:**

   * Run all SQL queries and provide screenshots of both the code and the resulting output.




## Sample Screenshots and Results:

### 1. View for vendor info and products from 2002 onwards**
#### Code:
![Image](https://github.com/user-attachments/assets/1c150a2e-531e-4fd7-b4bb-b4ad5ed9e502)

### 2. View for products priced between 100 and 150**
#### Code:
![Image](https://github.com/user-attachments/assets/fd544999-24dc-4903-9593-cb488638f984)


### 3. View to calculate total product price from selected vendors**
#### Code:
![Image](https://github.com/user-attachments/assets/5ebde779-e65e-473f-8351-dc80c18f5487)

### 4. Stored procedure to update vendor name**
#### Code:
![Image](https://github.com/user-attachments/assets/147a990a-f3e2-4b83-9cc5-9184f16b404d)

### 5. Function to filter products by vendor code and state**
#### Code:
![Image](https://github.com/user-attachments/assets/341fddba-eda9-4300-b0db-7b0c1dbfe148)


### 1. View for vendor info and products from 2002 onwards**
#### Output:
![Image](https://github.com/user-attachments/assets/79c654d6-eca7-45e9-b2fc-ac90494a3814)

### 2. View for products priced between 100 and 150**
#### Output:
![Image](https://github.com/user-attachments/assets/9c13cdb5-0484-4b60-a0e2-d0b877b8afac)

### 3. View to calculate total product price from selected vendors**
#### Output:
![Image](https://github.com/user-attachments/assets/1c2551bb-3702-4587-ae9e-fb15f2e1c940)

### 4. Stored procedure to update vendor name**
#### Output:
![Image](https://github.com/user-attachments/assets/2bb74d65-5b0e-48d2-9135-c9ea7fe44eb5)

### 5. Function to filter products by vendor code and state**
#### Output:
![Image](https://github.com/user-attachments/assets/15366e21-88cd-4605-b552-3d380599cbe1)
