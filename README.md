Online Quiz Web App
=========

This project uses:
* [Django](https://docs.djangoproject.com/en/4.0/) as backend framework
* [Postgres](https://www.postgresql.org/about/news/postgresql-14-released-2318/) as a database
  


After cloning this code:
* install Django : `pip install django`
* install Postgresql
* `cd` to the project `(.../pro3/online_quiz)` directory
* `python manage.py makemigrations`
* `python manage.py migrate`
* `python manage.py runserver`
* go to `http://127.0.0.1:8000/` to see the active website
* go to `http://127.0.0.1:8000/admin` to see the admin interface


*It might not be working as the postgres database is local (not on the cloud) at the moment.*
*Will fix this later*.
*if you just wanna play around with django you don't need to use Postges, just use the default Sqlite database come along with Django.*
