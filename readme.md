# Building an application contains two pages -
* Login screen - where users will enter email and password and submit (authentication). Don't accept anything except email. 
* Landing page - Based of result of the authentication app will show another page with error or success

### Language Preferred: ​ Java, node, python (any of three)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
#### Django Install
1. Set up your development structure:

```
$ git clone https://github.com/django/django.git
$ python -m pip install -e django/
$ python -m django --version
```

2. Make sure that you have Git installed and that you can run its commands from a shell. (Enter git help at a shell prompt to test this.
3. Check out this project's main  branch like so:

```$ git clone https://github.com/nafizzzzzzzzzz/signInLoginDSI
```

3. To exit the virtualenv, type the following command:
```$ deactivate```

#### Project run on the server
```
$ cd signInLoginDSI/signIn/
$ python manage.py runserver
```
4. This will prompt like -
```
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
May 15, 2020 - 11:46:18
Django version 3.0.6, using settings 'signIn.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.


```
5. Need to go to url and type http://127.0.0.1:8000/ in the browser to run this project 

## Built With
* Django ([Django Documentation](https://docs.djangoproject.com/en/3.0/))


