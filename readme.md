# Simple reactApp running in Django

## How to run it
Clone repository

Python3 and pip must be installed. Create virtual environment

``` $ python3 -m venv venv```

Activate virtual env

``` $ source venv/bin/activate```

Do Python dependencies installing 

``` (venv)$ pip install -r requirements.txt ```

Go to React app and make build (Better in a different shell)

``` $ cd reactapp/ ```

``` $ npm run build ```

Start Django server

``` $ python manage.py runserver ```

In navigator, go to http://127.0.0.1:8000/
