=====
Usage
=====

To use Django Tabulator in a project, add it to your `INSTALLED_APPS`:

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
