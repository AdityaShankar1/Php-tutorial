# PHP Travel Management System (Implementation)
A comprehensive, full-stack web application designed to manage tour bookings, user inquiries, and administrative packages. This project was implemented as a study of PHP PDO and MySQL database architecture, following a professional development template.

## 🛠 Features & Functionality
### Admin Dashboard
Package Management: Create, Update, and Delete tour packages with dynamic image uploads.
Booking Control: Review user bookings and update their status (Confirmed/Cancelled).
Issue Management: Track and resolve user-generated tickets and inquiries.
User Analytics: Monitor the number of registered users and platform activity.

### User Features
Authentication: Secure Sign-up and Sign-in functionality.
Tour Booking: Real-time booking of travel packages with automatic price calculation.
Support System: Generate tickets for complaints and track history of inquiries.
Account Management: User profile updates and password security.

### 💻 Technical Stack
Language: PHP 7.4+ (using PDO for secure database queries)
Database: MySQL
Frontend: Bootstrap, CSS, JavaScript, HTML5
Environment: Developed and tested on MAMP (macOS)

### 🚀 Local Installation (MAMP)
To run this project locally on a Mac using MAMP, follow these steps:
1. File SetupMove the project folder to your MAMP document root:
   /Applications/MAMP/htdocs/tms
2. Database SetupOpen phpMyAdmin (http://localhost:8888/phpMyAdmin).
3. Create a new database named tms.
4. Select the tms database and click the Import tab.
5. Upload the tms.sql file located in the root directory.
6. ConfigurationThe project is configured for MAMP's default credentials.
7. Ensure both /includes/config.php and /admin/includes/config.php contain:PHPdefine('DB_HOST','localhost');

## 📜 Credits & Attributions
Original Project Creator: Anuj Kumar
Original Source: PHPGurukul - [Tourism Management System](https://phpgurukul.com/tourism-management-system-free-download/)
Refactored/Implemented by: Aditya Shankar (as part of a PHP development tutorial)
