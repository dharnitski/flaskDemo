# Demo Flask App

Code for [Flask Tutorial](https://flask.palletsprojects.com/en/1.1.x/tutorial/)

## Prerequisites

* Python3
* Pip
* [Pipenv](https://pipenv-fork.readthedocs.io/en/latest/#install-pipenv-today)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/installation/#installation)


## How to setup dependencies

    $ pipenv shell
    $ pipenv install

## How to run App

    $ export FLASK_APP=flaskr
    $ export FLASK_ENV=development
    $ flask run

# How to run tests

Just tests:

    $ pytest

Tests with coverage:

    $ coverage run -m pytest
    $ coverage report
    $ coverage report

Open `htmlcov/index.html` in your browser to see the report