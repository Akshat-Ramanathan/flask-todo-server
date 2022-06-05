Simple Flask Todo App using SQLAlchemy and SQLite database.
For styling [semantic-ui](https://semantic-ui.com/) is used.

### Setup

Create project with virtual environment

```console
mkdir todo-app
cd todo-app
py -m venv flaskenv
```

Activate it

```console
flaskenv\Scripts\activate.bat
```

Install Flask and SQLAlchemy plugin

```console
pip install Flask
pip install Flask-SQLAlchemy
```

Set environment variable

```console
set FLASK_APP=app.py
set FLASK_ENV=development
```


Run the app
```console
py app.py
```
