Django Flat Responsive
======================

Description
-----------

**django-flat-responsive** is an extension for Django admin and
`django-flat-theme <https://github.com/elky/django-flat-theme/>`_.
This app adds CSS file which contains specific media queries for
mobile devices, such as phones and tablets.


Installation
------------

Install via pip:
``pip install django-flat-responsive``

**For Django 1.9+**

Put ``flat_responsive`` app in your *INSTALLED\_APPS* **before**
``django.contrib.admin``:

 ::

     INSTALLED_APPS = (
         ...
         'flat_responsive',
         'django.contrib.admin',
         ...
     )


**For older Django versions**

If you use Django version older than 1.9 this app will work properly only
in pair with `django-flat-theme <https://github.com/elky/django-flat-theme/>`_.
Put ``flat_responsive`` app in your *INSTALLED\_APPS* **before** ``flat``:

 ::

     INSTALLED_APPS = (
         ...
         'flat_responsive',
         'flat',
         'django.contrib.admin',
         ...
     )


Compatibility
~~~~~~~~~~~~~

Works in modern mobile browsers which support `CSS Flxebox <http://caniuse.com/#search=flexbox>`_.


Testing
~~~~~~~

Tested in:

- iOS Safari 9+
- Android Browser 4.4
- Chrome for iOS 53
- Chrome for Android 53

If you found any issues or want this app to support other browser versions -
please report `here <https://github.com/elky/django-flat-responsive/issues/>`_.


Screenshots
~~~~~~~~~~~

**Login page**

|1|

------------

**Dashboard**

|2|

------------

**Calendar widget**

|3|

.. |1| image:: https://cloud.githubusercontent.com/assets/209663/20430873/f001c6ee-adea-11e6-9695-df9957db09ce.png
.. |2| image:: https://cloud.githubusercontent.com/assets/209663/20430878/f72836ce-adea-11e6-8517-ef6d2fddd241.png
.. |3| image:: https://cloud.githubusercontent.com/assets/209663/20430883/fee78e00-adea-11e6-9bcb-8cac5a314094.png
