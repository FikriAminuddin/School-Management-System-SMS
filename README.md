
---

# Student Management System

## Introduction
The Student Management System is a web-based application built using PHP and MySQL. It aims to streamline the management of student-related activities within educational institutions. Traditionally, these tasks are handled manually, leading to inefficiencies in time and cost. This system automates various processes to enhance efficiency and effectiveness.

## Project Requirements
- **Project Name**: Student Management System in PHP
- **Language Used**: PHP 5.6, PHP 7.x
- **Database**: MySQL 5.x
- **User Interface Design**: HTML, AJAX, jQuery, JavaScript
- **Web Browser Compatibility**: Mozilla Firefox, Google Chrome, Internet Explorer 8, Opera
- **Software**: XAMPP, Wamp, MAMP, LAMP (anyone)

## How to Run the Student Management Project using PHP and MySQL
1. **Download the project zip file**
2. **Extract the file and copy the `studentms` folder**
3. **Paste inside the root directory** (for XAMPP `xampp/htdocs`, for Wamp `wamp/www`, for LAMP `var/www/Html`)
4. **Open PHPMyAdmin** (http://localhost/phpmyadmin)
5. **Create a database** with the name `studentmsdb`
6. **Import `studentmsdb.sql` file** (found inside the zip package in the SQL file folder) into the `studentmsdb` database
7. **Run the script** http://localhost/studentms

### Admin Credential
- **Username:** admin
- **Password:** Test@123

### Credential for Student / User panel:
- **Username:** anujk3
- **Password:** Test@123

Or register a new Student/User.

## Project Modules
### Admin
- **Dashboard**: Overview of system statistics such as Total Classes, Total Students, Notices, etc.
- **Class Management**: CRUD operations for managing classes.
- **Student Management**: CRUD operations for managing students.
- **Notice Management**: CRUD operations for managing notices.
- **Public Notices**: Management of public notices.
- **Pages Management**: Management of static pages like About Us and Contact Us.
- **Search**: Ability to search students by their student ID.
- **Reports**: Generation of reports on student registrations within specific periods.
- **Profile Management**: Update profile information, change password, and password recovery.

### User (Students)
- **Dashboard**: Welcome page for students.
- **View Notices**: Access notices published by administrators.
- **Profile Management**: Update profile information, change password, and password recovery.

### User (Non-Registered)
- **Home**: Welcome page for non-registered users.
- **About**: Access the About Us page.
- **Contact**: Access the Contact Us page.

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Configure your web server (e.g., Apache) and database server (MySQL).
3. Import the database schema provided (`database.sql`) into your MySQL server.
4. Update the database connection settings in `config.php`.
5. Access the application via a web browser.

## Usage
- **Admin**: Login with admin credentials to access admin functionalities.
- **Students**: Login with student credentials to access student functionalities.
- **Non-Registered Users**: Access public pages like Home, About, and Contact.

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests to propose changes.

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to further customize this README to suit your project's specific details and structure. Replace `<repository-url>` with your actual GitHub repository URL.