# Apache Cassandra Lab

## Installation Instructions

1. **Install Java 8**  
   Install Java 8 using Homebrew:
   ```bash
   brew tap AdoptOpenJDK/openjdk
   brew install --cask adoptopenjdk8
2. **Install Xcode for Cassandra Dependencies**
   ```bash
   xcode-select --install
3. **Install Cassandra**
   ```bash
   brew install cassandra
4. **Install Cassandra Shell**
   ```bash
   pip install cqlsh

## Tasks
## 1. Create a Keyspace
### Create a keyspace named "my_keyspace" with a replication factor of 2 using SimpleStrategy.
<img width="562" alt="Task1" src="https://github.com/user-attachments/assets/8b63a439-196f-4f53-88ef-4509a9a6aa08"><br>

## 2. Create a Table
### Inside "my_keyspace", create a table called "users"
<img width="294" alt="Screenshot 2024-10-30 at 11 21 04 PM" src="https://github.com/user-attachments/assets/1e59db05-16a4-449c-95e1-522492fdf46f"><br>

## 3. Insert Data
### Insert 3 sample rows into the users table
<img width="548" alt="Screenshot 2024-10-30 at 11 22 44 PM" src="https://github.com/user-attachments/assets/435941eb-1bf3-41fa-ad96-f73fe086e66c"><br>

## 4. Query Data
### Write a query to retrieve all the rows from the users table
<img width="653" alt="Screenshot 2024-10-30 at 11 24 36 PM" src="https://github.com/user-attachments/assets/2d9af8d2-4286-420d-b073-82bc51be1d5f"><br>

## 5. Update Data
### Update the email address of one of the users (e.g., update Alice's email)
<img width="891" alt="Screenshot 2024-10-30 at 11 28 20 PM" src="https://github.com/user-attachments/assets/d3ce5e95-032f-489e-a023-18d55e4ead62"><br>

## 6. Delete Data
### Delete one of the users (e.g., delete Bob) based on user_id
<img width="650" alt="Screenshot 2024-10-30 at 11 29 30 PM" src="https://github.com/user-attachments/assets/bf668b60-dff8-4a60-8796-6a001b90c71c"><br>

## 7. Create a New Table with Clustering Key
### Create a new table called orders that tracks multiple orders per user
<img width="294" alt="Screenshot 2024-10-30 at 11 31 52 PM" src="https://github.com/user-attachments/assets/cdd2afce-2f66-46df-9ca3-e58c97cc0dad"><br>

## 8. Perform a Range Query
### Query the orders table to retrieve all orders for a specific user within a date range
<img width="895" alt="Screenshot 2024-10-30 at 11 36 59 PM" src="https://github.com/user-attachments/assets/125a1155-ffe4-4903-9a7b-6f8a8ff879f8"><br>

## 9. Create an Index
### Create an index on the email column in the users table to improve query performance
<img width="347" alt="Screenshot 2024-10-30 at 11 38 30 PM" src="https://github.com/user-attachments/assets/37088b6c-ad3b-47ed-94a7-f87c98c01869"><br>

## 10. Backup and Restore Data
### Perform a simple backup of the "my_keyspace" data using the nodetool utility, then simulate a restore
<img width="802" alt="Screenshot 2024-10-30 at 11 39 30 PM" src="https://github.com/user-attachments/assets/567c8fa8-a006-47c8-a0d1-62800d8a6333"><br>

## 11. Count Rows in a Table
### Write a query to count the number of rows in the users table
<img width="342" alt="Screenshot 2024-10-30 at 11 40 32 PM" src="https://github.com/user-attachments/assets/1adac087-6041-4214-ad0c-1aed63067597"><br>

## 12. Drop a Table
### Drop the "orders" table from the "my_spaces"
<img width="281" alt="Screenshot 2024-10-30 at 11 42 09 PM" src="https://github.com/user-attachments/assets/cae8e2a6-c50d-4a2f-8063-5aa83d81a615"><br>

