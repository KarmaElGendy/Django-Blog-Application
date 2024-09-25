# Django Blog Application

This is a Django Blog Application where users can create, edit, and delete blog posts, as well as register, log in, and manage profiles with profile pictures.

![NewPost](https://github.com/KarmaElGendy/Django-Blog-Application/blob/main/media/New.png)

## Features
- User authentication: Register, log in, log out.
- Blog post CRUD: Create, read, update, delete blog posts.
- User profile management: Upload and display profile pictures.
- Responsive design using Bootstrap and Django Crispy Forms.

## Project Structure

The following is the folder structure of this Django Blog Application:

```
C:. │ db.sqlite3 # SQLite database file for the project │ manage.py # Django command-line utility for administrative tasks │ posts.json # JSON file for initial post data (if applicable) │ ├───blog # Blog app for the project │ │ admin.py # Admin configuration for the blog app │ │ apps.py # Configuration for the blog app │ │ models.py # Blog app models (data structure) │ │ tests.py # Unit tests for the blog app │ │ urls.py # URL routing for the blog app │ │ views.py # Views handling HTTP requests for the blog app │ │ init.py # Python package initialization for the blog app │ │ │ ├───migrations # Database migrations for the blog app │ │ │ 0001_initial.py # First migration for the blog app │ │ │ init.py # Python package initialization for migrations │ │ │ │ │ └───pycache # Compiled Python bytecode │ │ 0001_initial.cpython-310.pyc │ │ init.cpython-310.pyc
│ │ │ ├───static # Static files for the blog app │ │ └───blog │ │ main.css # CSS file for styling the blog pages │ │ │ ├───templates # HTML templates for the blog app │ │ └───blog │ │ about.html # About page template │ │ base.html # Base template used across the blog app │ │ home.html # Home page template │ │ post_confirm_delete.html # Template for confirming post deletion │ │ post_detail.html # Template for individual post details │ │ post_form.html # Template for creating or editing posts │ │ user_posts.html # Template for displaying a user's posts │ │ │ └───pycache # Compiled Python bytecode for the blog app │ admin.cpython-310.pyc │ apps.cpython-310.pyc │ models.cpython-310.pyc │ urls.cpython-310.pyc │ views.cpython-310.pyc │ init.cpython-310.pyc │ ├───django_project # Main Django project configuration │ │ asgi.py # ASGI configuration for asynchronous support │ │ settings.py # Main settings for the Django project │ │ urls.py # Main URL routing for the Django project │ │ wsgi.py # WSGI configuration for deployment │ │ init.py # Python package initialization │ │ │ └───pycache # Compiled Python bytecode for the project │ settings.cpython-310.pyc │ urls.cpython-310.pyc │ wsgi.cpython-310.pyc │ init.cpython-310.pyc │ ├───media # Media files uploaded by users │ │ default.jpg # Default image for profiles or posts │ │ Profile.png # Sample profile image │ │ home.png # Screenshot or image for home page │ │ login.png # Screenshot of the login page │ │ register.png # Screenshot of the registration page │ │ reset.png # Screenshot of the password reset page │ │ ss1.png # Additional screenshot (optional) │ │ │ └───profile_pics # Folder for storing user profile pictures │ 5010324.JPG # Example profile picture │ └───users # Users app for handling user-related functionality │ admin.py # Admin configuration for the users app │ apps.py # Configuration for the users app │ forms.py # Forms for user-related actions (e.g., registration) │ models.py # Models for user data │ signals.py # Signals for actions like profile creation on user sign-up │ tests.py # Unit tests for the users app │ views.py # Views for handling HTTP requests in the users app │ init.py # Python package initialization for the users app │ ├───migrations # Database migrations for the users app │ │ 0001_initial.py # First migration for the users app │ │ init.py # Python package initialization for migrations │ │ │ └───pycache # Compiled Python bytecode for the users app │ 0001_initial.cpython-310.pyc
│ init.cpython-310.pyc
│ ├───templates # HTML templates for the users app │ └───users │ login.html # Template for the login page │ logout.html # Template for the logout page │ password_reset.html # Template for password reset request page │ password_reset_confirm.html # Template for password reset confirmation │ password_reset_done.html # Template after successful password reset request │ profile.html # Template for the user profile page │ register.html # Template for the user registration page │ └───pycache # Compiled Python bytecode for the users app

```
## Getting Started

### Prerequisites
- Python 3.x installed on your system.
- Django framework (listed in `requirements.txt`).

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/KarmaElGendy/Django-Blog-Application.git
    ```

2. Navigate into the project directory:

    ```bash
    cd Django-Blog-Application
    ```

3. Requirements

To run this project, you need to install the following Python packages. You can install them using `pip`:

- asgiref==3.8.1
- crispy-bootstrap4==2024.1
- Django==5.1.1
- django-crispy-forms==2.3
- pillow==10.4.0
- sqlparse==0.5.1
- typing_extensions==4.12.2
- tzdata==2024.1

You can install these dependencies by running:

```bash
pip install -r requirements.txt
```

4. Set up the database:

    ```bash
    python manage.py migrate
    ```

5. Create a superuser to access the Django admin panel:

    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

7. Open your web browser and navigate to:

    ```bash
    http://127.0.0.1:8000/
    ```

## Usage

- Register as a new user or log in with the superuser credentials.
- Create, edit, and delete blog posts.
- Update your profile and upload profile pictures.

## Screenshots

### Homepage

### View Your Profile
![Profile](https://github.com/KarmaElGendy/Django-Blog-Application/blob/main/media/Profile.png)

### Login
![Login](https://github.com/KarmaElGendy/Django-Blog-Application/blob/main/media/login.png)

### Reset Password
![Reset Password](https://github.com/KarmaElGendy/Django-Blog-Application/blob/main/media/reset.png)

### Sign Up/Register
![Register](https://github.com/KarmaElGendy/Django-Blog-Application/blob/main/media/register.png)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bugs or feature requests.
