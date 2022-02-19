This is a very simple mock Flask application. Be sure to install a virtual env and .gitignore the filename, in my case, 'env'.

It is best practice to .gitignore your .env file. I have done so here, along with pycache and my virtual environment, 'env'. 

The essential contents for a simple Flask app are as follows:

FLASK_APP = app

FLASK_ENV = development

Some helpful commands for getting started with Flask on Windows:

virtualenv name_of_env

pip install flask

pip install python-dotenv

flask run

CTRL + C to quit
