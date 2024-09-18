# Online Education Portal

## Description
An online education portal built with PHP that allows users to access courses, take quizzes, and track their progress. This project aims to provide a comprehensive platform for online learning.

## Features
- User Registration and Authentication
- Course Management
- Quiz and Assessment System
- Progress Tracking
- Admin Dashboard
- Student Dashboard
- Parents Dashboard
- Teacher Dashboard
  
## Technologies Used
- PHP
- MySQL
- HTML/CSS
- JavaScript
- Bootstrap

## Installation

### Prerequisites
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Apache or Nginx server

### Steps
1. **Clone the repository**
    ```bash
    git https://github.com/dm-mishra1578/E-Learning.git
    cd online-education-portal
    ```

2. **Set up the database**
    - Create a MySQL database.
    - Import the provided SQL file to set up the database schema.
    ```sql
    CREATE DATABASE education_portal;
    USE education_portal;
    SOURCE path/to/your/sql/file.sql;
    ```

3. **Configure the application**
    - Rename `config.example.php` to `config.php`.
    - Update the database configuration in `config.php`.
    ```php
    define('DB_HOST', 'localhost');
    define('DB_USER', 'your_db_user');
    define('DB_PASS', 'your_db_password');
    define('DB_NAME', 'education_portal');
    ```

4. **Start the server**
    - If using Apache, place the project in the `htdocs` directory.
    - If using Nginx, configure the server block to point to the project directory.
    - Start the server and navigate to `http://localhost/online-education-portal`.

## Usage
- **Admin**: Log in to the admin dashboard to manage courses, quizzes, and users.
- **User**: Register and log in to access courses, take quizzes, and track progress.

## Screenshots
!Home Page
!Course Page

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.



