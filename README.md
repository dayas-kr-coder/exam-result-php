# PHP CRUD with Login & Logout

This repository houses a straightforward PHP application that facilitates CRUD operations (Create, Read, Update, Delete). Additionally, it incorporates secure user authentication for login and logout functionality.

## Database Setup

To employ this application, follow these steps:

1. Create a MySQL database named `exam_result` by executing the following SQL statement:

   ```sql
   CREATE SCHEMA `exam_result`;
   ```

2. Switch to the newly created database using:

   ```sql
   USE `exam_result`;
   ```

## Features

- **User Authentication**: Ensures secure login and logout functionality.
- **CRUD Operations**: Allows users to Create, Read, Update, and Delete exam results.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/dayas-kr-coder/exam-result-php.git
   ```

2. Configure your web server to serve the application.

3. Edit the `config.php` file to set up the database connection, providing your database credentials.

4. Import the SQL file (`exam_result.sql`) into your MySQL database to create the required tables.

5. Access the application through your web browser.

## Directory Structure

<!-- - **css**: Holds stylesheets for the application. -->

- **js**: Includes JavaScript files if needed.
- **includes**: Contains PHP files for reusable components.
- **pages**: Includes PHP files for different pages of the application.
- **sql**: Holds the SQL file for creating the database schema.

## Contributing

Feel free to contribute to this project by submitting bug reports, feature requests, or pull requests. Your feedback is valuable!

## License

This project is licensed under the [MIT License](LICENSE).
