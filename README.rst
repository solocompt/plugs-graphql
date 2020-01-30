=============================
Plugs GraphQL
=============================

.. image:: https://badge.fury.io/py/plugs-graphql.svg
    :target: https://badge.fury.io/py/plugs-graphql

.. image:: https://travis-ci.org/ricardolobo/plugs-graphql.svg?branch=master
    :target: https://travis-ci.org/ricardolobo/plugs-graphql

.. image:: https://codecov.io/gh/ricardolobo/plugs-graphql/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/ricardolobo/plugs-graphql

Your project description goes here

Documentation
-------------

The full documentation is at https://plugs-graphql.readthedocs.io.

Quickstart
----------

Install Plugs GraphQL::

    pip install plugs-graphql

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'plugs_graphql.apps.PlugsGraphqlConfig',
        ...
    )

Add Plugs GraphQL's URL patterns:

.. code-block:: python

    from plugs_graphql import urls as plugs_graphql_urls


    urlpatterns = [
        ...
        url(r'^', include(plugs_graphql_urls)),
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

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
