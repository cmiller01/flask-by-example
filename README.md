based off a great demo here: https://realpython.com/blog/python/flask-by-example-part-1-project-setup/

# Installation
* Python 2.7 & pip
* `pip install -r requirements.txt`
* Also you'll need redis and postgres installed (`apt-get` or `brew install`)

# Running
* Start redis: `redis-server`
* Postgres should be running: `pg_ctl status`
* Worker: `python worker.py`
* Server: `python manage.py runserver`
