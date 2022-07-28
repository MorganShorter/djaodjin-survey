DjaoDjin survey
================

The Django app implements a simple survey app. Surveys can also be run
in quizz mode.


Five minutes evaluation
=======================

The source code is bundled with a sample django project.

    $ virtualenv *virtual_env_dir*
    $ cd *virtual_env_dir*
    $ source bin/activate
    $ pip install -r testsite/requirements.txt
    $ make initdb
    $ python manage.py runserver

    # Visit url at http://localhost:8000/
    # You can use username: donny, password: yoyo to test the manager options.

Releases
========

Tested with

- **Python:** 3.7, **Django:** 3.2 ([LTS](https://www.djangoproject.com/download/)), **Django Rest Framework:** 3.12
- **Python:** 3.10, **Django:** 4.0 (latest), **Django Rest Framework:** 3.12
- **Python:** 2.7, **Django:** 1.11 (legacy), **Django Rest Framework:** 3.9.4


0.6.2

  * insures answers appear only once in final output
  * stores data points with baseline when necessary
  * adds aggregate filter values APIs

[previous release notes](changelog)


Models have been completely re-designed between version 0.1.7 and 0.2.0
