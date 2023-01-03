# Bugtracker
 Project Management tool for software projects built using Django-React with MySQL database

INSTRUCTIONS:

1) in the command prompt run "git clone https://github.com/maxim-pre/Bugtracker.git"
2) open up the settings file in django and choose unique password for the database (initially set to just "password")
3) open up MySQL workbench and make a new connection to local host (make sure to set the connection password as the same in django settings)
4) create a new schema called "bugtracker"
5) in django-backend run:
        pipenv install --> pipenv shell --> python manage.py makemigrations --> python manage.py migrate
6) create a superuser using "python manage.py createsuperuser"
7) lastly run "python manage.py runserver" in django-backend and "npm start" in react-frontend



