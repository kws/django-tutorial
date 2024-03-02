# Django Tutorials

This repository holds an implementation of the Django 5.0 tutorial. The tutorial is available at [Django 5.0 Tutorial](https://docs.djangoproject.com/en/5.0/intro/tutorial01/).

The purpose of this is to be able to provide a number of additional tutorials building upon the core one. 

The code in the django core tutorial are Copyright (c) Django Software Foundation and individual contributors. See <https://github.com/django/django/blob/main/LICENSE> for full license.

## Getting Started

To use this repository, you will need to have Python 3.8 or later installed as well as git. 

To get started, you will need to clone the repository and then create a virtual environment. 

```bash
# Clone the repository
$ git clone https://github.com/kws/django-tutorial.git

# Change into the directory
$ cd django-tutorial

# Create a virtual environment
$ python -m venv venv

# Activate the virtual environment
$ source venv/bin/activate

# Install the requirements
$ pip install -r requirements.txt

# Run the migrations
$ python manage.py migrate

# Create a superuser
$ python manage.py createsuperuser

# Run the server
$ python manage.py runserver
```

You should now be able to access the site at <http://localhost:8000/polls>.
