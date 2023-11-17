# Flask API

Effortlessly manage your bookmarks with this powerful REST API. Our Bookmark Management API provides a seamless solution for organizing and accessing your bookmarks through simple and intuitive endpoints.

![image](https://github.com/MichaelBenIsrael/bookmarker-api-flask/assets/73841983/432bafab-d604-4dc3-8b7e-99c3e47d969e)


### Dependencies

* [Python](https://www.python.org/) - Programming Language
* [Flask](https://flask.palletsprojects.com/) - The framework used
* [SQLAlchemy](https://docs.sqlalchemy.org/) - ORM
* [Pydantic](https://pydantic-docs.helpmanual.io/) - Data validation
* [Alembic](https://alembic.sqlalchemy.org/) - Database Migrations
* [Pip](https://pypi.org/project/pip/) - Dependency Management
* [RESTful](https://restfulapi.net/) - REST docs

### Virtual environments

```
$ sudo apt-get install python-virtualenv
$ python3 -m venv venv
$ . venv/bin/activate
$ pip install Flask
```

Install all project dependencies using:

```
$ pip install -r requirements.txt
```

### Running
 
```
$ export FLASK_APP=app.py
$ export FLASK_ENV=development
$ python -m flask run
```


## Contributing

This API was developed based on:

[Flask documentation](https://flask.palletsprojects.com/)

[REST APIs with Flask and Python](https://www.udemy.com/rest-api-flask-and-python/) 

[The Ultimate Flask Course](https://www.udemy.com/the-ultimate-flask-course) 
