=====
djbs
=====

djbs is a simple collection of filters and templates for building Django
interfaces with Bootstrap v4

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "djbs" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'djbs',
    ]

2. Include or extend the templates under djbs/ as necessary.

3. If you need to use the included filters directly, they can be imported via::

    {% load djbs_extras %}
