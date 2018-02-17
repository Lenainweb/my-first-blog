# Demo app in Djando
![python3.x](https://img.shields.io/badge/python-3.x-brightgreen.svg) ![django2.x](https://img.shields.io/badge/%20Django-2.0.1-green.svg)

## Setting up

##### Clone the repo

```
$ git clone https://github.com/Lenainweb/my-first-blog.git
$ cd my-first-blog
```

##### Initialize a virtualenv

```
$ python3 -m venv venv
$ . venv/bin/activate
```

##### Install the dependencies

```
$ pip install -r requirements.txt
```

##### Create the database

```
$ python manage.py migrate
```

## Running the server

```
$ python manage.py runserver
