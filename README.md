# Fibonacci_Series_Django
In thios project the front-end shows for the taking a number shows the Nth number of Fibonacci Series Number.

#Unzip the file django-fibonacci.zip
Go to djnago_fibonacci folder

#Install The requirements of this project
Create Virtual environmentfor installation of dependancies.
>>virtualenv name_of_virtual_env
>>cd name_of_virtualenv/Script
>>actiavte

#Now your virtual environment is activated

Install the requirements of the project
Go to Project directory
>>pip install -r requirement.txt

Go to settings.py file and change the database configuration
I have used PostgreSQL as Database

Open psql
>>CREATE DATABASE database_name;

Migrate table into Database
Open CMD into your manage.py directory
>>python manage.py makemigrations
>>python manage.py migrate
>>python manage.py runserver


Open browser and hit url for your output>>127.0.0.1:8000
#Enter number that shows you result and also stored in Database

