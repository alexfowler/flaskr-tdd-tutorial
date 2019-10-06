# flaskr-tdd-tutorial
My code from working through this tutorial: https://github.com/mjhea0/flaskr-tdd

Pre-requisites
- pipenv
- python 3.7.3
- Heroku CLI

How to start app
```
$ cd <path-to-app>/flaskr-tdd
$ pipenv shell
$ pipenv install
$ python app.py
```

How to run tests
```
$ python app-test.py
```

How to deploy to Heroku
```
$ pipenv install gunicorn==19.9.0
$ heroku create
$ git push heroku master
```

Pipenv specifics
---
How to install new package using pipenv
```
$ pipenv install <package>
```

How to properly deactivate pipenv (while in pipenv venv)
```
$ deactivate
$ exit
```
