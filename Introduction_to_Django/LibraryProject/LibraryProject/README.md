# LibraryProject

This is the initial Django project setup for the **Introduction to Django** module.

## Steps Followed
1. Installed Django using `pip install django`.
2. Created a new project with `django-admin startproject LibraryProject`.
3. Started the development server using `python manage.py runserver`.

## Project Structure
- **manage.py**: A command-line tool for running project tasks.
- **LibraryProject/settings.py**: Main configuration file for the project (database, apps, middleware, etc.).
- **LibraryProject/urls.py**: Defines URL routes for the project.
- **LibraryProject/wsgi.py / asgi.py**: Entry points for WSGI/ASGI servers.

## Running the Project
```bash
python manage.py runserver
