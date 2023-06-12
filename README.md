# Authentication App

This is a web application built with Django, MySQL, and Bootstrap that provides user registration, login, and a dashboard functionality.

## Features

- User registration with first name, last name, email, password, and confirm password fields.
- Encrypted password storage using Django's built-in password hashing.
- User login with email and password.
- Dashboard page displaying a welcome message and current time.
- User logout functionality.

## Prerequisites

Make sure you have the following installed:

- Python 3.x
- Django
- MySQL database
- Bootstrap CSS framework

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/authentication-app.git

    Navigate to the project directory:

cd authentication-app

Install the Python dependencies:

pip install -r requirements.txt

Set up the MySQL database:

    Create a new MySQL database for the application.
    Update the database settings in settings.py with your MySQL database credentials.

Apply the database migrations:


python manage.py migrate

Run the development server:
```
    python manage.py runserver
```

Access the application in your web browser at http://localhost:8000.

## Usage

    Register a new user by providing the required information on the registration page.
    Login with your email and password on the login page.
    After successful login, you will be redirected to the dashboard page.
    On the dashboard page, you will see a welcome message and the current time.
    To log out, click on the "Logout" link.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or new features to propose, please open an issue or submit a pull request.
License

This project is licensed under the MIT License.

Feel free to make any adjustments or additions to the content based on your project requirements.