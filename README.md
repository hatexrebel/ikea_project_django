KEA-Inspired Django Website

1. Project Overview

This project is an independent educational website inspired by IKEA's home furnishing and furniture theme. It is developed using the Django web framework and demonstrates website development, template inheritance, navigation, static file management, and user authentication.

Project Type: Django Web Development Project
Framework: Django 4.2.30
Language: Python
Database: SQLite

2. Project Objectives

Develop a multi-page website using Django.

Implement reusable templates using Django template inheritance.

Create functional navigation between website pages.

Implement user registration, login, and logout.

Apply custom CSS styling and responsive layouts.

Understand Django views, URL routing, forms, and authentication.

3. Technologies Used

Python 3.9.6

Django 4.2.30

HTML5

CSS3

SQLite

Visual Studio Code

4. Features Implemented

Website Pages

Home: Landing page with a hero section and navigation.

Products: Product categories and visual content.

About IKEA: Information about the website's theme, vision, and design philosophy.

Login: User authentication using Django's built-in authentication system.

Sign Up: User registration with form validation.

Authentication

User registration.

Login using username and password.

Logout functionality.

Password confirmation validation.

Duplicate email validation.

Django password hashing.

Success and error messages.

Design and Navigation

Shared header and footer.

Reusable base template.

Named Django URL patterns.

Custom CSS styling.

Responsive layouts.

Working internal navigation links.

5. Project Structure

ikea_project/
│
├── .venv/
│
└── ikea_project/
    │
    ├── manage.py
    ├── ikea_project/
    │   ├── settings.py
    │   ├── urls.py
    │   ├── asgi.py
    │   └── wsgi.py
    │
    ├── website/
    │   ├── migrations/
    │   ├── views.py
    │   ├── urls.py
    │   ├── forms.py
    │   ├── models.py
    │   └── admin.py
    │
    ├── templates/
    │   ├── base.html
    │   ├── home.html
    │   ├── products.html
    │   ├── about.html
    │   ├── login.html
    │   └── signup.html
    │
    └── css/
        ├── base.css
        ├── home.css
        ├── products.css
        ├── about.css
        └── auth.css

6. Installation and Setup

Prerequisites

Python installed.

Django 4.2.30.

A terminal or command-line interface.

Step 1: Navigate to the project directory

Open the terminal in the directory containing manage.py.

Step 2: Activate the virtual environment

On macOS/Linux:

source .venv/bin/activate

Step 3: Install Django

pip install django==4.2.30

Step 4: Apply database migrations

python3 manage.py migrate

Step 5: Start the development server

python3 manage.py runserver

Open the following address in your browser:

http://127.0.0.1:8000/

7. Website URLs

Page

URL

Home

/

Products

/products/

About IKEA

/about/

Login

/login/

Sign Up

/signup/

8. Database and Authentication

The project uses SQLite as its database through Django's default database configuration.

Django's built-in authentication system handles user registration, password hashing, login sessions, and logout.

The UserCreationForm functionality is extended through a custom SignUpForm to collect additional user information and validate email uniqueness.

Database migrations are managed using Django's migration system.

9. Running the Project

After completing the installation steps, execute:

python3 manage.py runserver

The website will be available at:

http://127.0.0.1:8000/

10. Project Disclaimer

This is an independent educational project inspired by IKEA's website and home furnishing theme. It is not affiliated with, sponsored by, or officially associated with IKEA.

End of Project Documentation