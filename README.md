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

## Extending the Tutorial

The tutorial is broken into a number of tags and branches. Each tag or branch represents a step in the tutorial.

Each part of the original tutorial is tagged with the part number. For example, the first part of the tutorial is tagged with `DT-PART1` etc. through `DT-PART7`:

* [DT-PART1][DT-PART1]: Core tutorial part 1 - <https://docs.djangoproject.com/en/5.0/intro/tutorial01/>
* [DT-PART2][DT-PART2]: Core tutorial part 2 - <https://docs.djangoproject.com/en/5.0/intro/tutorial02/>
* [DT-PART3][DT-PART3]: Core tutorial part 3 - <https://docs.djangoproject.com/en/5.0/intro/tutorial03/>
* [DT-PART4][DT-PART4]: Core tutorial part 4 - <https://docs.djangoproject.com/en/5.0/intro/tutorial04/>
* [DT-PART5][DT-PART5]: Core tutorial part 5 - <https://docs.djangoproject.com/en/5.0/intro/tutorial05/>
* [DT-PART6][DT-PART6]: Core tutorial part 6 - <https://docs.djangoproject.com/en/5.0/intro/tutorial06/>
* [DT-PART7][DT-PART7]: Core tutorial part 7 - <https://docs.djangoproject.com/en/5.0/intro/tutorial07/>

[DT-PART1]: https://github.com/kws/django-tutorial/releases/tag/DT-PART1
[DT-PART2]: https://github.com/kws/django-tutorial/releases/tag/DT-PART2
[DT-PART3]: https://github.com/kws/django-tutorial/releases/tag/DT-PART3
[DT-PART4]: https://github.com/kws/django-tutorial/releases/tag/DT-PART4
[DT-PART5]: https://github.com/kws/django-tutorial/releases/tag/DT-PART5
[DT-PART6]: https://github.com/kws/django-tutorial/releases/tag/DT-PART6
[DT-PART7]: https://github.com/kws/django-tutorial/releases/tag/DT-PART7