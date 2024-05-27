# DjangoRest_Mongo_db

we’re gonna create Python 3/Django & MongoDB CRUD example with Django Rest Framework for building Rest Apis.


Technology

    - Python 3.7
    - Django 2.1.15
    - Django Rest Framework 3.11.0
    - djongo 1.3.1
    - django-cors-headers 3.2.1
    - MongoDB 3.4 or higher


    
# Create the project directory
mkdir tutorial
cd tutorial

# Create a virtual environment to isolate our package dependencies locally
python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install Django and Django REST framework into the virtual environment
pip install django
pip install djangorestframework

# Set up a new project with a single application
django-admin startproject tutorial .  # Note the trailing '.' character
cd tutorial
django-admin startapp tutorials
cd ..
