# Flask App
The following project was built during my course with Bottega.  It has full CRUD functionality.
> Dependencies Documentation
- FLASK
  - http://flask.palletsprojects.com/en/1.1.x/
- FLASK-MARSHMALLOW
  - https://flask-marshmallow.readthedocs.io/en/latest/
- FLASK-SQLALCHEMY
  - https://flask-sqlalchemy.palletsprojects.com/en/2.x/
- MARSHMALLOW-SQLALCHEMY
  - https://marshmallow-sqlalchemy.readthedocs.io/en/latest/
## Commands to follow after downloading
- Install all the dependencies
```
$ pipenv install
```
### Create Database
- If you need to create a database.  Hop into a python repl and run the following commands.
- When you're done you should have an app.sqlite file.  That file will be your database.
```
>>> from app import db
>>> db.create_all()
```
### Starting your server
- Enter a pipenv shell first
```
$ pipenv shell
```
- Start the server
```
$ python app.py
```
### How to run queries
- Post a guide
```
Route: localhost:5000/guide
Method: POST
Body: {
    "title": "Your cool title",
    "content": "Your amazing content"
}
Content-type: JSON
```
- Get all guides
```
Route: localhost:5000/guides
Method: GET
```
- Get a single guide
```
- The id will be dynamic.  The id that you input will return the guide that you want to collect from the database.
Route: localhost:5000/guide/id
Method: GET
```
- PUT a single guide
```
- The id will be dynamic.  The id that you input will be the guide that you want to edit from the database.
Route: localhost:5000/guide/id
Method: PUT
Body: {
    "title": "Your Updated Title",
    "content": "Your Updated Content"
}
Content-type: JSON
```
- DELETE a single guide
```
- The id will be dynamic.  The id that you input will be the guide that you want to delete from the database.
Route: localhost:5000/guide/id
Method: DELETE
```
### Exit your pipenv shell
- how to exit a pipshell
```
$ exit
```

GIT STEPS
how to start a new git rep
$ git init
add all items to the repo
$ git add .
commit your changes to be saved
  - Best practice to say initial commit when its the first commit
$ git commit -m "commit message"
For your first time go to github and create a new repo
copy the second option and paste into your terminal
Afterwards you will only need to do the following command to push your code to githut
$ git push


references:
Dependencies Documentation
```
https://flask-marshmallow.readthedocs.io/en/latest/
https://flask-sqlalchemy.palletsprojects.com/en/2.x/
https://marshmallow-sqlalchemy.readthedocs.io/en/latest/
