A Word About This Django Fork
=============================

This is an unofficial fork of Django_, which focuses entirely on backporting
official, publicly-announced security fixes to Django 1.6.11. It does not
contain any other bug fixes or features, and any branches other than
``security-backports/1.6.x`` are unlikely to be up-to-date.

Django 1.6.x is the last release cycle of Django to support Python 2.6, but
both Django 1.6.x and Python 2.6.x are no longer officially supported by
either project, and will no longer be receiving any official security fixes.

We recognize that many organizations and products are still tied to these
releases, which is why we've built this fork. However, we *strongly* recommend
that you use modern, official versions of both Django and Python, if at all
possible.

We're not guaranteeing long-term support on this codebase. We're maintaining
this for `Review Board`_ customers so long as we support the versions
currently using Django 1.6.x.

We're also not actively looking for new security vulnerabilities. If you find
a new vulnerability in this release, check to be sure it does not apply to any
other versions currently supported by the Django project.

.. _Django: https://www.djangoproject.com/
.. _`Review Board`: https://www.reviewboard.org/


Downloads
---------

All security backport releases will be posted to our `downloads page`_. They
are not available via PyPI.

You can verify builds against our `PGP key`_ (285291B34ED1F993).

Current releases:

* **1.6.11.7** - March 6, 2018
  (`Release notes <https://github.com/beanbaginc/django/blob/security-backports/1.6.x/docs/releases/1.6.11.7.txt>`__)

  `Django-1.6.11.7.tar.gz <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.7.tar.gz>`_
  (`pgp <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.7.tar.gz.asc>`__,
  `sha256 <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.7.sha256sum>`__)

* **1.6.11.6** - April 4, 2017
  (`Release notes <https://github.com/beanbaginc/django/blob/security-backports/1.6.x/docs/releases/1.6.11.6.txt>`__)

  `Django-1.6.11.6.tar.gz <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.6.tar.gz>`_
  (`pgp <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.6.tar.gz.asc>`__,
  `sha256 <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.6.sha256sum>`__)

* **1.6.11.5** - November 1, 2016
  (`Release notes <https://github.com/beanbaginc/django/blob/security-backports/1.6.x/docs/releases/1.6.11.5.txt>`__)

  `Django-1.6.11.5.tar.gz <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.5.tar.gz>`_
  (`pgp <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.5.tar.gz.asc>`__,
  `sha256 <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.5.sha256sum>`__)

* **1.6.11.4** - September 26, 2016
  (`Release notes <https://github.com/beanbaginc/django/blob/security-backports/1.6.x/docs/releases/1.6.11.4.txt>`__)

  `Django-1.6.11.4.tar.gz <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.4.tar.gz>`_
  (`pgp <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.4.tar.gz.asc>`__,
  `sha256 <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.4.sha256sum>`__)

* **1.6.11.3** - March 1, 2016
  (`Release notes <https://github.com/beanbaginc/django/blob/security-backports/1.6.x/docs/releases/1.6.11.3.txt>`__)

  `Django-1.6.11.3.tar.gz <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.3.tar.gz>`_
  (`pgp <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.3.tar.gz.asc>`__,
  `sha256 <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.3.sha256sum>`__)

* **1.6.11.2** - November 24, 2015
  (`Release notes <https://github.com/beanbaginc/django/blob/security-backports/1.6.x/docs/releases/1.6.11.2.txt>`__)

  `Django-1.6.11.2.tar.gz <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.2.tar.gz>`_
  (`pgp <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.2.tar.gz.asc>`__,
  `sha256 <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.2.sha256sum>`__)

* **1.6.11.1** - August 18, 2015
  (`Release notes <https://github.com/beanbaginc/django/blob/security-backports/1.6.x/docs/releases/1.6.11.1.txt>`__)

  `Django-1.6.11.1.tar.gz <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.1.tar.gz#md5=b2aff4ed0d3757cdde3200900c9080a8>`_
  (`pgp <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.1.tar.gz.asc#md5=15bad0e2d1d831511eb964bf975f6e62>`__,
  `sha256 <https://downloads.reviewboard.org/releases/Django/1.6/Django-1.6.11.1.sha256sum#md5=925f259c4325cd2d5329382b9cd3f85f>`__)


.. _`PGP key`: https://keybase.io/beanbag


Reporting Bugs
--------------

If you hit any bugs with this release, please verify whether they still occur
with the official Django 1.6.11 release, or ideally, the latest supported
version.

If they're absolutely upstream Django bugs, you can file it against the
`Django bug tracker`_. However, if they're our problem, please file it against
`our bug tracker`_.

.. _`downloads page`: https://downloads.reviewboard.org/releases/Django/1.6/index.html
.. _`Django bug tracker`: https://code.djangoproject.com/newticket
.. _`our bug tracker`: https://www.reviewboard.org/bugs/new/


About Django
------------

*(The following is the official information about Django itself. Please
remember not to bother them about anything related to this fork.)*

Django is a high-level Python Web framework that encourages rapid development
and clean, pragmatic design. Thanks for checking it out.

All documentation is in the "docs" directory and online at
http://docs.djangoproject.com/en/dev/. If you're just getting started, here's
how we recommend you read the docs:

* First, read docs/intro/install.txt for instructions on installing Django.

* Next, work through the tutorials in order (docs/intro/tutorial01.txt,
  docs/intro/tutorial02.txt, etc.).

* If you want to set up an actual deployment server, read
  docs/howto/deployment/index.txt for instructions.

* You'll probably want to read through the topical guides (in docs/topics)
  next; from there you can jump to the HOWTOs (in docs/howto) for specific
  problems, and check out the reference (docs/ref) for gory details.

* See docs/README for instructions on building an HTML version of the docs.

Docs are updated rigorously. If you find any problems in the docs, or think they
should be clarified in any way, please take 30 seconds to fill out a ticket
here:

http://code.djangoproject.com/newticket

To get more help:

* Join the #django channel on irc.freenode.net. Lots of helpful people hang out
  there. Read the archives at http://django-irc-logs.com/.

* Join the django-users mailing list, or read the archives, at
  http://groups.google.com/group/django-users.

To contribute to Django:

* Check out http://www.djangoproject.com/community/ for information about
  getting involved.

To run Django's test suite:

* Follow the instructions in the "Unit tests" section of
  docs/internals/contributing/writing-code/unit-tests.txt, published online at
  https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/#running-the-unit-tests
