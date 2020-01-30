=====
Usage
=====

To use Plugs GraphQL in a project, add it to your `INSTALLED_APPS`:

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
