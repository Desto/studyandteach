studyandteach
=============

Studyandteach.com project

To use this locally you need to create a local database. This can be done by executing db_create.py script. I highly recommend you setup some other database than sqlite3 in development (for example postgresql).
Backend is built using Flask, required add-ons include atleast Flask-SQLAlchemy, Flask-Social and their dependencies.

TODOS:
-------------
- Database table optimization
- Facebook & Twitter login with Flask-Social
- Frontend, especially CSS :) (Frontend pretty much does not exist at the moment)
- RESTful API
- Unit testing
