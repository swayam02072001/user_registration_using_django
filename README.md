# User Registration using Django

This project is a user registration system built using Django, a high-level Python web framework. It allows users to create accounts by providing their username, email address, and password. After registration, users can log in to access additional features or content.

## Features

- User-friendly registration form with input validation.
- Secure storage of user passwords using Django's built-in authentication system.
- Email verification to confirm the user's email address.
- Customizable user profile settings.
- Integration with Django's admin panel for user management.

## Technologies Used

- **Django**: Python web framework used for backend development.
- **HTML/CSS**: Frontend styling and structure.
- **Bootstrap**: Frontend framework for responsive design and UI components.
- **SQLite**: Default database system provided by Django for storing user data.
- **SMTP**: Simple Mail Transfer Protocol used for sending email verification messages.

## Getting Started

### Prerequisites

- Python 3.12
- Django

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/swayam02072001/user-registration.git
    ```

2. Navigate to the project directory:

    ```bash
    cd user-registration
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Django server:

    ```bash
    python manage.py runserver
    ```

5. Open your web browser and go to [http://localhost:8000](http://localhost:8000) to access the application.

## Usage

1. Navigate to the registration page.

2. Fill out the registration form with your desired username, email address, and password.

3. Click on the "Register" button to submit the form.

4. Check your email inbox for a verification link and follow the instructions to verify your email address.

5. Once verified, log in with your credentials to access additional features or content.

## Customization

- **Styling**: Modify the HTML/CSS files to customize the appearance of the registration form and user interface.
  
- **Functionality**: Extend the Django user model or views to add additional fields or functionality to the registration process.
