# Modern Login Form Using PHP, SQL, and XAMPP
## Overview
This README provides an overview of the features and installation procedure for a basic login system implemented with PHP, SQL, and XAMPP.


## Table of Contents

- [Installation](#Installation)
- [Usage](#Usage)
- [Project Discription](#Project-Description)
- [Achievements](#Achievements)
- [Screenshots](#Screenshots)

## Installation
#### 1. Download and Install XAMPP:
   - Download XAMPP from the official website and follow the installation instructions for your operating system.
   - Start the Apache and MySQL services from the XAMPP Control Panel.

#### 2. Database Setup:
   - Open phpMyAdmin by visiting [http://localhost/phpmyadmin](http://localhost/phpmyadmin) in your web browser. 
   - Create a new database named `login_system`.
   - Import the `database.sql` file provided in the repository to create the necessary tables.

#### 3. Project Setup:
   - Clone or download the project files into the `htdocs` directory of your XAMPP installation (typically located at `C:\xampp\htdocs` on Windows).
   - Ensure that the file structure remains intact, including `index.php`, `login.php`, `registration.php`, `logout.php`, `database.php`, and `style.css`.

#### 4. Configuration:
   - Open `database.php` and update the database connection settings if necessary (hostname, username, password, and database name).

#### 5. Accessing the Application:
   - Open your web browser and navigate to `http://localhost/your-project-folder/login.php`.
   - You should now see the login page. You can register as a new user or log in with existing credentials.

#### 6. Customization:
   - Customize the CSS styles in `style.css` to match your project's design requirements.
   - Modify the PHP files (`index.php`, `login.php`, `registration.php`, `logout.php`, `database.php`) to add additional features or customize the behavior as needed.

### Usage Guide

#### 1. Registration:

1. **Accessing the Registration Page**:
   - Open your web browser and navigate to `http://localhost/your-project-folder/registration.php`.
   - You should see a registration form with fields for Full Name, Email, Password, and Repeat Password.

2. **Filling out the Registration Form**:
   - Enter your full name, email address, and desired password into the respective fields.
   - Make sure to enter a valid email address and a password that meets the specified requirements (at least 8 characters long).

3. **Submitting the Registration Form**:
   - Click on the "Register" button to submit the registration form.
   - If there are any errors in the form data (e.g., empty fields, invalid email, password mismatch), appropriate error messages will be displayed.
   - If the registration is successful, you will see a success message indicating that you have been registered successfully.

#### 2. Login:

1. **Accessing the Login Page**:
   - If you're not already on the login page, navigate to `http://localhost/your-project-folder/login.php`.

2. **Entering Login Credentials**:
   - Enter your registered email address and password into the respective fields on the login form.

3. **Submitting the Login Form**:
   - Click on the "Login" button to submit the login form.
   - If the email or password is incorrect, you will see an error message indicating that the credentials do not match.
   - If the login is successful, you will be redirected to the user dashboard (`index.php`) where you will see a welcome message indicating that you have successfully logged in.

#### 3. User Dashboard:

1. **Accessing the User Dashboard**:
   - Upon successful login, you will be redirected to the user dashboard (`index.php`).

2. **Viewing Welcome Message**:
   - You will see a welcome message indicating that you have successfully logged in.

3. **Logging Out**:
   - To log out, click on the "Logout" link provided on the dashboard.
   - You will be logged out of the system and redirected to the login page (`login.php`).

#### 4. Additional Notes:

- **Session Management**: Your login state is maintained using PHP session management. Once you log in, you remain logged in until you explicitly log out or close the browser.
- **Password Security**: Passwords are securely hashed using PHP's `password_hash()` function before storing them in the database.
- **Error Handling**: The system provides error messages for invalid form submissions and authentication failures to guide users in providing correct information.
- **Database Integration**: User registration data is stored in a MySQL database, and login credentials are verified against this database during the authentication process.

## Project Description
This project provides a basic yet functional login system that can be used as a foundation for building more complex web applications requiring user authentication. It demonstrates the implementation of essential features such as user registration, login, session management, password security, and database integration using PHP, MySQL, and XAMPP.

## Achievements
**Efficient Database Management:** Demonstrated proficiency in database management by designing efficient database schemas, optimizing queries for improved performance, and implementing data validation techniques, showcasing expertise in handling and manipulating large datasets effectively.

**Seamless Integration of Backend Systems:** Successfully integrated backend systems, including user authentication and session management, ensuring smooth and secure user interactions with the application, highlighting adeptness in backend development and system integration.

**Responsive and Accessible Design:** Implemented responsive design principles and accessibility features, ensuring compatibility across various devices and catering to users with diverse accessibility needs, showcasing a commitment to inclusive design practices and user-centric development.
