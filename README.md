# Django-X

Django-X is a Twitter-inspired social media platform built with Django. This application allows users to create, view, edit, and delete tweets in a clean, modern interface with Bootstrap 5.

Demo Video: https://www.loom.com/share/1329da4a3442429291c49d8cdee92edb?sid=7e2733ec-413a-4bca-bd1a-5f8cdbcf09d4

## Features

- **User Authentication**: Register, login, and logout functionality
- **Tweet Management**: Create, view, edit, and delete tweets
- **Image Support**: Upload images with tweets
- **Responsive Design**: Built with Bootstrap 5 for a responsive UI
- **Dark Mode**: Modern dark theme interface

## Technologies Used

- Django 5.1.7
- Python 3.11+
- Bootstrap 5.3.3
- SQLite (default database)
- HTML/CSS/JavaScript

## Installation

Follow these steps to set up Django-X on your local machine:

### Prerequisites

- Python 3.11 or higher
- pip (Python package manager)
- Git

### Clone the Repository

```bash
git clone https://github.com/yourusername/Django-X.git
cd Django-X

# On Windows
python -m venv .venv
.venv\Scripts\activate

# On macOS/Linux
python -m venv .venv
source .venv/bin/activate

# Installs all the requirements
pip install -r requirements.txt

# Create migrations and migrate
cd DjangoX
python manage.py makemigrations
python manage.py migrate

# Create superuser to login as admin
python manage.py createsuperuser

# Run the server
python manage.py runserver

````
