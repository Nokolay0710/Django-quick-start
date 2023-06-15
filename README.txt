mkdir New project
cd New project
pipenv install request
pipenv shell
pipenv install django==4.2.0
django-admin startproject config .
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
Starting development server at http://127.0.0.1:8000/
Rocket!
Quit the server with Ctrl+C.