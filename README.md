django-tecdoc
=============

django integration with tecdoc db in mysql form

WORK IN PROGRESS!

Installation
============================

`pip install django-tecdoc`

or

`pip install -e https://github.com/suvit/django-tecdoc#egg=tecdoc-dev`


Add separate db for `tecdoc`

    DATABASES = {
       'default': {
           ...
       },
       'tecdoc': {
           'ENGINE': 'django.db.backends.mysql',
           'NAME': 'tecdoc',
           'HOST': 'host',
           'USER': 'user',
           'PASSWORD': 'pass',
       }
    }

Settings
------------

for settings used `django-appconf`

You can overwrite several settings
* DATABASE
* DB_PREFIX
* LANG_ID
* FILE_HOST
