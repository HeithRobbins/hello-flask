# Flask App

There following project was built dring my course with bottega. It has full CRUD functionality.


### create database
if you need to create a database. hop into a python repl and run the following cammands
when you're done you should have an app.sqlite file. that file will be your database

from app import dp 
db.create_all()

get put post patch delete


### Create Database
- If you need to create a database.  Hop into a python repl and run the following commands.
- When you're done you should have an app.sqlite file.  That file will be your database.
```
>>> from app import db
>>> db.create_all()
```

PIPENV STEPS
How to make a pip environment
- Traverse to the folder you want to make an environment
- In your terminal run this command
$ pipenv --three
Open vscode
$ code .
Check your pip file to make sure it has python 3
Go back to your terminal and install your dependencies
$ pipenv install dependenci_name
To enter your pip environment after installing all dependencies run the following command
$ pipenv shell
how to exit a pipshell
$ exit

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
https://flask-marshmallow.readthedocs.io/en/latest/
https://flask-sqlalchemy.palletsprojects.com/en/2.x/
https://marshmallow-sqlalchemy.readthedocs.io/en/latest/
