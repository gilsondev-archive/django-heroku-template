*****************************************
django-heroku-template
*****************************************

Project template used for projects that use Heroku.


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


------------------------------------------
Using bootstrap-django-heroku
------------------------------------------

`bootstrap-django-heroku`_ is a fork of the `virtualenv-bootstrap`_ which creates the virtual environment and installs the dependencies in the file requirements.txt in the folder bootstrap.

1. Checkout project bootstrap-django-heroku:

.. code-block:: bash

    $ git clone git@github.com:gilsondev/bootstrap-django-heroku.git project_name


2. Bootstrap the development environment:

.. code-block:: bash

    $ cd project_name
    $ python bootstrap


3. Activate environment:

.. code-block:: bash

    $ source bin/activate


4. Create project:

.. code-block:: bash

    $ django-admin.py startproject --template=https://github.com/gilsondev/django-heroku-template/zipball/master --extension=py,rst,dev --name Procfile project_name .


.. _bootstrap-django-heroku: https://github.com/gilsondev/bootstrap-django-heroku
.. _virtualenv-bootstrap: https://github.com/henriquebastos/virtualenv-bootstrap
