# django-todolist

Simple todolist write in django for general use and pipeline automation..

### Tech

Dillinger uses a number of open source projects to work properly:

* [Django] - Django makes it easier to build better Web apps more quickly and with less code.
* [pyenv] - The pyenv module provides support for creating lightweight “virtual environments” with their own site directories
* [MySQL] - MySQL is an Oracle-backed open source relational database management system (RDBMS) based on Structured Query Language (SQL).


### Installation

Install the dependencies and start the server.

```sh
$ cd django-todolist
$ pip install -r requirements.txt
$ python manage.py migrate # Running the migrations
$ python manage.py createsuperuser # Create a superuser
$ python manage.py runserver
```
teste