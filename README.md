# Authentication System

## Overview
This authentication system provides user registration, login, and session management functionalities. It ensures secure authentication using PHP and MySQL.

## Features
- User Registration
- User Login
- User Logout
- Password Hashing for Security
- Session Management

## Technologies Used
- PHP
- MySQL
- HTML & CSS

## Installation

### Prerequisites
- A web server (e.g., Apache with PHP support)
- MySQL database
- PHP 7 or later

### Setup Steps
1. Clone the repository or download the files.
   ```sh
   git clone https://github.com/yourusername/authentication-system.git
   ```
2. Import the `database.sql` file into your MySQL database.
3. Update the `db.php` file with your database credentials.
4. Place the project files in your web server's root directory (e.g., `htdocs` for XAMPP).
5. Start the Apache and MySQL services.
6. Open your browser and navigate to `http://localhost/authentication-system/`.

## File Structure
```
/authentication-system/
│-- index.html         # Home Page
│-- register.html      # Registration Page
│-- register.php       # Registration Script
│-- login.php          # Login Script
│-- logout.php         # Logout Script
│-- dashboard.php      # Protected Dashboard Page
│-- db.php             # Database Configuration
│-- LICENSE            # License Information
```

## Usage
### Register a New User
1. Navigate to `register.html`.
2. Enter the required details and submit the form.
3. Your account will be created and stored in the database.

### Login
1. Navigate to `login.php`.
2. Enter your registered email and password.
3. Upon successful login, you will be redirected to `dashboard.php`.

### Logout
- Click the logout button to end the session and return to the login page.

## Security Measures
- Passwords are securely hashed using `password_hash()`.
- User sessions are managed using `session_start()` and properly destroyed on logout.

## License
This project is open-source and free to use under the MIT License.

## Contact
For any issues or feature requests, please open an issue on GitHub
