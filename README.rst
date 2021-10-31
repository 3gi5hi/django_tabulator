=============================
Django Tabulator
=============================

.. image:: https://badge.fury.io/py/django_tabulator.svg
    :target: https://badge.fury.io/py/django_tabulator

.. image:: https://travis-ci.org/shijaku/django_tabulator.svg?branch=master
    :target: https://travis-ci.org/shijaku/django_tabulator

.. image:: https://codecov.io/gh/shijaku/django_tabulator/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/shijaku/django_tabulator

Your project description goes here

Documentation
-------------

The full documentation is at https://django_tabulator.readthedocs.io.

Quickstart
----------

Install Django Tabulator::

    pip install django_tabulator

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_tabulator.apps.DjangoTabulatorConfig',
        ...
    )

Add Django Tabulator's URL patterns:

.. code-block:: python

    from django_tabulator import urls as django_tabulator_urls


    urlpatterns = [
        ...
        url(r'^', include(django_tabulator_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox


Development commands
---------------------

::

    pip install -r requirements_dev.txt
    invoke -l


Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
