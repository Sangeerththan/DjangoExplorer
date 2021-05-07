django-admin startproject explore
cd explore/
python3 manage.py runserver
python3 manage.py migrate
python3 manage.py runserver

Change your models (in models.py).
Run python manage.py makemigrations to create migrations for those changes
Run python manage.py migrate to apply those changes to the database.

