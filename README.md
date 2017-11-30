# REST-API-with-Flask-Restless-and-SQLAlchemy


## Summary
* This is a simple CRUD APP project that shows how to auto-generate a REST API from a handful of SQLalchemy models. This means full CRUD (POST, GET, PUT, DELETE) endpoint generation for each SQLalchemy model defined.

* Big shout out and thank you to Sean Harrington at http://thelaziestprogrammer.com/sharrington/web-development/sqlalchemy-defined-rest-api


## Environment Set up
1. Create a project in the root directory
    mkdir automagic_api

2. Create and activate a virtualenv
    cd automagic_api;

    #virtualenv env; latest version of Python and book_api_blueprint

    source env/bin/activate

3. Install flask_restless and sqlalchemy
    pip install flask-restless sqlalchemy
