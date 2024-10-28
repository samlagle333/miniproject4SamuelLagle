### INF601 - Advanced Programming in Python
### Samuel Lagle
### Mini Project 4


# Mini Project 4

## Description

This is a web-based application that utilizes the Django framework. The application itself allows for an admin to create questions and choices for users to vote on and tally the results.

## Getting Started

```
python manage.py makemigrations (this will create any SQL entries that need to go into the database)
python manage.py migrate (this will apply the migrations)
python manage.py createsuperuser (this will create the administrator login for your /admin)
```

### Dependencies

```
pip install -r requirements.txt
```

### Executing program

```
python manage.py runserver
```

## Output

This should run Django to start the server. Next, you can open a browser and type in the URL "http://127.0.0.1:8000" which will allow access to the site. 

## Authors

Samuel Lagle

## Acknowledgments

Inspiration, code snippets, etc.
* [chatgpt](https://chatgpt.com/share/671bf733-c230-8010-84ec-80cdaacb8b4f)
* [Django](https://docs.djangoproject.com/en/4.2/intro/)
* [Bootstrap](https://getbootstrap.com/docs/5.3/components/modal/)
