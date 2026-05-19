KrishiMitra 🌱

KrishiMitra is a PHP-based web application designed to support farmers by providing agricultural information and assistance through an easy-to-use web platform.

Features
User-friendly interface
Agricultural support system
Database integration
Responsive design
Easy navigation
Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL
Server: Apache (XAMPP)
Prerequisites

Before running this project, make sure you have:

XAMPP installed
PHP installed
MySQL installed
A web browser (Chrome recommended)

Installation and Setup
Step 1: Clone the Repository
git clone https://github.com/PotdarSumit/krihsimitra.git
Step 2: Move Project Folder

Move the cloned project folder to:

C:\xampp\htdocs\

Your final folder path should be:

C:\xampp\htdocs\krihsimitra
Step 3: Start Apache and MySQL

Open XAMPP Control Panel and start:

Apache
MySQL
Step 4: Create Database

Open phpMyAdmin in your browser:

http://localhost/phpmyadmin

Create a new database named:

krishimitra
Step 5: Import Database

Import the SQL file available in the project folder into the created database.

Step 6: Configure Database Connection

Open your database configuration file and update these details:

$host = "localhost";
$username = "root";
$password = "";
$database = "krishimitra";
Step 7: Run the Project

Open your browser and visit:

http://localhost/krihsimitra
Project Structure
krihsimitra/
│── assets/
│── css/
│── js/
│── images/
│── database/
│── index.php
│── config.php
Future Enhancements
Improved farmer dashboard
Weather integration
Crop recommendation system
Mobile responsiveness improvements
Author

Sumit Potdar

GitHub: PotdarSumit

License

This project is for educational and learning purposes.
