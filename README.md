# Quick Knowledge Django

A [Miguel](http://twitter.com/oieusouamiguell)'s repository for Django studies. Inspired by [@alalbuquerque](http://github.com/alalbuquerque) repositories - thank you, sweetie.

## Reference
* [WTF is Django](#wtf-is-django)
* [How to install](#how-to-install)
* [Basics about django-admin boilerplate](#basics-about-django-admin-boilerplate)


## WTF is Django?
Django is a Python framework.

## How to install


## Basics about django-admin boilerplate

	├── manage.py
	├── myproject/
	|   ├── __init__.py
	|   ├── settings.py
	|   ├── urls.py
	|   ├── wsgi.py	
  
  
 ### manage.py
Run Django's admin commands like `runserver`.

### __init__.py


### settings.py
Django's configuration file. This file can be modified and have options like `DEBUG=TRUE` and `SECRET_KEY`.

 ### urls.py 
 Definition of URLs from a *regular expression* that indicates which python function (*views.py*) will be executed when we are inside the page (url).

### wsgi.py
Protocol to run app with server. More infos [here](https://docs.djangoproject.com/en/2.0/howto/deployment/wsgi/).

