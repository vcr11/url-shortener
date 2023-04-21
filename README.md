
# URL Shortener App

A Django URL Shortener App created with Django 3.0 and Python 3.10 to shorten any URL given. 

## How to Setup in Localhost

1. Clone this repository.
2. Open the cloned repository.
3. Install dependencies using ``pip install -r requirements.txt``
**OR**
Install ``pipenv`` using ``pip install pipenv`` and initialise a Virtual Machine using ``pipenv install`` in the directory.
4. Set environment variables like `SECRET_KEY`, `DEBUG_VALUE`.
5. Run the Django Server using ``python manage.py runserver`` and then goto ``localhost:8000`` or ``127.0.0.1:8000`` and see the server running.

### Environment Variables:

`SECRET_KEY`: Django secret key which can be any long hexadecimal value. Django recommends *atleast* **50 characters** to make it secure.
`DEBUG_VALUE`: Set it as **"True"** for Debug environment and **"False"** for Production.


## Features

- Can shorten any url.
- Can see all the shortened urls created with it.
- Can choose any custom value to shorten the url.
