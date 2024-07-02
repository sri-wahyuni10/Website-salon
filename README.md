# Website-salon
this is my website salon i created 
you can make program for connected the database 

this is example for connect database
<?php
// db.php

// Database connection settings
// Connect to database
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "customer_review";

// Create a new MySQLi object
$conn = new mysqli($servername, $username, $password, $dbname);

// Check connection
if ($conn->connect_error) {
    die("Connection failed: ". $conn->connect_error);
}
?>
