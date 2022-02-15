# WisdomPets-Django
Simple website of a pet shelter, containing a list of pets loaded from database and their details.
Website made with Django, following the Learning Django LinkedIn course.


![screen](https://user-images.githubusercontent.com/36500094/154070486-211e5720-95d6-482c-a0bb-7d1b4c7a2149.PNG)

## Useful commands
- Create the project base structure
```
django-admin startproject wisdompets
```
- Run the server
```
python manage.py runserver
```
- Create an application for the website
```
python manage.py startapp adoptions
```
- Create script to execute db migration
```
python manage.py makemigrations
```
- Show list of available migrations
```
python manage.py showmigrations
```
- Execute migration
```
python manage.py migrate
```
- Script to load some data into the database
```
python manage.py load_pet_data
```
- Create a superuser for the website
```
python manage.py createsuperuser
```
default superuser in this project: ``` admin:admin ```
