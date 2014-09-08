=========
Collections
=========

Collection plugin for django CMS 3.

Installation
-----------

This plugin requires 'django CMS' 3.0 or higher to be properly installed.

To get started using "djangocms_collection":

1. Install "djangocms_collection" in your projects 'virtualenv'

2. Add "djangocms_collection" to your INSTALLED_APPS settings like this::

    INSTALLED_APPS = (
        ...
        'djangocms_collection',
    )

3. Execute migration or syncdb to create the djangocms_collection models::

    $ python manage.py syncdb

    $ python manage.py migrate




