# POC for DRF with class based view. 

# api app is directory for Cart Based Views 

# Sqlite Database used

# Reference URL - https://stackabuse.com/creating-a-rest-api-with-django-rest-framework/

Finally, we can create a project and app, called api_app:

django-admin startproject shopping_cart
cd shopping_cart # Project contains app
python3 manage.py startapp api_app

# Migration of model in sqllite database
$ python3 manage.py migrate  # Initialize database
$ python3 manage.py createsuperuser # Prompts for username and password

$ python3 manage.py runserver  # Run Python Server
