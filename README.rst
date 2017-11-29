========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-dacase/badge/?style=flat
    :target: https://readthedocs.org/projects/python-dacase
    :alt: Documentation Status

.. |version| image:: https://img.shields.io/pypi/v/dacase.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/dacase

.. |commits-since| image:: https://img.shields.io/github/commits-since/dbl0null/python-dacase/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/dbl0null/python-dacase/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/dacase.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/dacase

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/dacase.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/dacase

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/dacase.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/dacase


.. end-badges

app for da case

* Free software: Apache Software License 2.0

Installation
============

::

    pip install dacase

Documentation
=============

https://python-dacase.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
