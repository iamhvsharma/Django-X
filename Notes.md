- Command to create virtual environment
``` bash
python3 -m venv .venv
.venv\Scripts\activate
```

- pip install django

- pip freeze > requirements.txt  (Write all the dependency in requirements.txt)

- django-admin startproject <project name>  (To start a django project)
cd projectname

python manage.py runserver


Starting migrations steps
python manage.py makemigrations
python manage.py migrate


Create a super user
python manage.py createsuperuser


Create new app in Django
python manage.py startapp tweet