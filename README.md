The OSQA project - open source Q&A system

setup
-----

copy `settings_local.py.dist` to `settings_local.py`, then `syncdb`, then `runserver`:

    $ cp settings_local.py.dist settings_local.py
    $ ./manage.py syncdb
    $ ./manage.py runserver