=====
Usage
=====

To use Nobinobi Stats in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'nobinobi_stats.apps.NobinobiStatsConfig',
        ...
    )

Add Nobinobi Stats's URL patterns:

.. code-block:: python

    from nobinobi_stats import urls as nobinobi_stats_urls


    urlpatterns = [
        ...
        url(r'^', include(nobinobi_stats_urls)),
        ...
    ]
