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
![Image](https://github.com/user-attachments/assets/588bcf3e-9c55-4b1b-9ce2-355c480fb1d0)
#### Output:
![Image](https://github.com/user-attachments/assets/b56d25dc-6312-494b-a192-5c76d125572d)

### 2. View for products priced between 100 and 150**

#### Code:
![Image](https://github.com/user-attachments/assets/f704bb34-abdc-4ca6-971b-597c7077044a)
#### Output:
![Image](https://github.com/user-attachments/assets/8bd906ef-22cc-46d6-9776-1239cfb210b8)

### 3. View to calculate total product price from selected vendors**

#### Code:
![Image](https://github.com/user-attachments/assets/b770922d-e6b9-4f25-83e1-b3b488d8abb2)
#### Output:
![Image](https://github.com/user-attachments/assets/660a718c-da43-4eb0-9f42-f19a60637c89)
### 4. Stored procedure to update vendor name**

#### Code:
![Image](https://github.com/user-attachments/assets/dca28b72-c223-42e4-9031-c6c1c2eaaf30)

#### Output:
![Image](https://github.com/user-attachments/assets/90f12ea7-f646-43f9-898f-a832b0a1a971)
### 5. Function to filter products by vendor code and state**

#### Code:
![Image](https://github.com/user-attachments/assets/9b42d3e9-a178-4430-be65-3fdf0abdc37b)
#### Output:
![Image](https://github.com/user-attachments/assets/9ccd3e8b-5f13-471c-b001-9cae3f2edfb0)
