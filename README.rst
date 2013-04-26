*****************************************
django-heroku-template
*****************************************

Project template used for projects that use Heroku. This project uses the `virtualenv-bootstrap`_ to create a virtualized environment, and install project dependencies.


------------------------------------------
How To Install
------------------------------------------

.. code-block:: bash

    django-admin.py startproject --template=https://github.com/gilsondev/django-heroku-template/zipball/master --extension=py,rst,dev --name Procfile project_name


=========================================
Dependencies
=========================================

* Django==1.5.1
* South==0.7.6
* Unipath==1.0
* dj-database-url==0.2.1
* gunicorn==0.17.4
* pytest-django==2.3.0

.. _virtualenv-bootstrap: https://github.com/henriquebastos/virtualenv-bootstrap
