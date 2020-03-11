Continuous Integration with Zuul
================================

Each change made to Stackalytics core code is tested with unit and integration
tests and style checks flake8.

Unit tests and style checks are performed on the public `OpenDev
Zuul <https://zuul.opendev.org/>`_. Unit tests are checked using
Python 2.7, Python 3.6, and Python 3.7.

The result of those checks and Unit tests are +1 or -1 to *Verify* column in a
code review from *Zuul* user.
