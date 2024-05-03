# Employee Leave Management System

This is a web application built with PHP and MySQL, designed as an Employee Leave Management System. Users can manage their leaves, including requesting, approving, and viewing leave history. The application features user authentication for different roles (employee and manager) and includes an email API for sending notifications and updates.

## Features

- **Manage Leaves**: Employees can request different types of leaves.
- **Leave Approval**: Managers can review and approve or reject leave requests.
- **Leave History**: Employees and managers can view leave history.
- **User Authentication**: Secure login and authentication for employees and managers.
- **Email Notifications**: Sends email notifications for leave request updates.

## Technology Stack

- **PHP**: Backend logic.
- **MySQL**: Database.
- **HTML, CSS**: Designing page layout.
- **JavaScript**: Frontend interactivity.
- **Email API**: For sending notifications to users' email addresses.

## Software and Tools Required

- PHP 7+
- MySQL
- Web server (e.g., Apache, Nginx)

## Getting Started

### Prerequisites

- PHP 7 or higher
- MySQL
- Web server with PHP support (e.g., Apache, Nginx)

### Installation

1. **Clone the repository**:

    ```shell
    git clone https://github.com/nandrehetan/Employee-Leave-Management.git
    ```

2. **Navigate to the project directory**:

    ```shell
    cd Employee-Leave-Management
    ```

3. **Import the database schema**:

    - Locate the `db` directory and import the provided SQL file into your MySQL database.

4. **Configure the database connection**:

    Update the database connection settings in the `config.php` file:

    ```php
    define('DB_HOST', 'your_host');
    define('DB_USER', 'your_username');
    define('DB_PASS', 'your_password');
    define('DB_NAME', 'your_database');
    ```

5. **Configure Email API settings**:

    Update the email API settings in the `config.php` file:

    ```php
    define('EMAIL_HOST', 'your_smtp_host');
    define('EMAIL_PORT', 'your_smtp_port');
    define('EMAIL_USERNAME', 'your_email');
    define('EMAIL_PASSWORD', 'your_email_password');
    ```

6. **Run the application**:

    - Start your web server and navigate to the project directory.

## Usage

Once the application is running, you can interact with it through the web interface:

- **Employees**: Log in to submit leave requests and view leave history.
- **Managers**: Log in to review and approve or reject leave requests.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check out the [issues page](https://github.com/yourusername/Employee-Leave-Management/issues).

## License

This project is licensed under the [MIT License](LICENSE).
