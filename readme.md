Simple Flask Todo App 

using SQLAlchemy & SQLite database.


Setup

Create project with virtual environment

mkdir 'myproject'
cd 'myproject'
python -m venv venv
Activate it

$ . venv/bin/activate

or for Windows

.\venv\Scripts\activate


Install Flask

pip install Flask
pip install Flask-SQLAlchemy

Set environment variables in terminal

$ export FLASK_APP=app.py
$ export FLASK_ENV=development

or for Windows

set FLASK_APP=app.py
set FLASK_ENV=development


Run the app

 flask run