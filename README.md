# Django Blog Application

This is a Django Blog Application where users can create, edit, and delete blog posts, as well as register, log in, and manage profiles with profile pictures.

![Home Page](https://github.com/KarmaElGendy/Django-Blog-Application/blob/main/media/home.png)

## Features
- User authentication: Register, log in, log out.
- Blog post CRUD: Create, read, update, delete blog posts.
- User profile management: Upload and display profile pictures.
- Responsive design using Bootstrap and Django Crispy Forms.

## Project Structure

The following is the folder structure of this Django Blog Application:

├───blog │ ├───migrations │ │ └───pycache │ ├───static │ │ └───blog │ ├───templates │ │ └───blog │ └───pycache ├───django_project │ └───pycache ├───media │ └───profile_pics └───users ├───migrations │ └───pycache ├───templates │ └───users └───pycache

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
