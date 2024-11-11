# Django Api Application

A simple to-do list application to implement CRUD (Create, Read, Update, Delete) method in a Django API to use it on a mobile or web application.

Built with ❤️ by SleentO Academy.

## Requirement

Python3 must be installed in your machine

## Packages used

* Django
* Django Rest Framework

## Setup

1. Clone the project

get the project from github by typing the following command

```sh
git clone git@github.com:sleento-academy/todolist-api-crud-app.git
```

2. Create a virtual environment

In the project folder, type the following command.

```sh
python3 -m venv env
```

3. Activate the virtual environment

```sh
source env/bin/activate
```

4. Install dependencies

```sh
pip install -r requirements.txt
```

5. Migrate the database

```sh
python manage.py migrate
```

6. Start the server

Start the server on your local machine, 0.0.0.0:8000 will use your PC network IP address and port 8000
```sh
python manage.py runserver 0.0.0.0:8000
```

----------