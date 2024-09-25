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
C:.
│   manage.py                 # Django management script
│   posts.json                # Example blog post data
│
├───blog                      # Blog app
│   ├───models.py             # Blog app models
│   ├───views.py              # Views for the blog
│   ├───urls.py               # URL patterns for the blog app
│   ├───templates             # Blog-related templates
│   └───static                # Blog-specific static files (CSS, JS)
│
├───django_project            # Project settings and configuration
│   ├───settings.py           # Main project settings
│   ├───urls.py               # Project-wide URL patterns
│
├───media                     # Folder for the default profile pic and uploaded images (profile pics, etc.)
│
└───users                     # User app for authentication
    ├───views.py              # Views for user authentication and profiles
    ├───models.py             # User models
    └───templates             # User-related templates (login, register, etc.)


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

3. Install the required dependencies:
   
    To run this project, you need to install the following Python packages.
    
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

5. Set up the database:

    ```bash
    python manage.py migrate
    ```

6. Create a superuser to access the Django admin panel:

    ```bash
    python manage.py createsuperuser
    ```

7. Run the development server:

    ```bash
    python manage.py runserver
    ```

8. Open your web browser and navigate to:

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
