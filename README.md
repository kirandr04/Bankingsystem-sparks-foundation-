# Bankingsystem-sparks-foundation-
The project has been completed during  one-month Web development Internship with The Sparks Foundation.
Create a simple dynamic website which has the following specs.
1. Start with creating a dummy data in database for upto 10 customers. Database options: Mysql, Mongo, Postgres, etc. Customers table will have basic fields such as name, email, current balance etc. Transfers table will record all transfers happened.
2. Flow: Home Page > View all Customers > Select and View one Customer > Transfer Money > Select customer to transfer to > View all Customers.
3. No Login Page. No User Creation. Only transfer of money between multiple users.
4. Host the website.
##Stack used:
	1.Front-end: HTML,CSS,JAVASCRIPT
	2.Back-end: PHP
	3.Database: Mysql
  
  ### Project code description
1. trial.php: This is the Home page of the banking wepsite project.<br>
2. viewCustomers.php: It displays the customers details after fetching the data  from the database.<br>
3. transfer.php: This is responsible for Money transfer after asking for id of payer and payee and amount.<br>
4. resultpage: This is the action page after user fills the form for transaction showcased by transfer.php. Here the actual transaction of money from database takes place. It is also responsible for error handling if any occurs in form filling. Also, it updates history table in DB which is keeping track of all transactions happened so far.<br>
5. recordspage.php: displays the transaction details of all the customers.<br>
6. navbar.php: Showcases the navigation bar at top of all pages.<br>
7. sprk_bank.sql: This is the database file made using MySQL DBMS. It consist of two tables accountdetails and history.<br>


