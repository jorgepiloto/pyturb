========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/pyturb/badge/?style=flat
    :target: https://readthedocs.org/projects/pyturb
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/jorgepiloto/pyturb.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/jorgepiloto/pyturb

.. |codecov| image:: https://codecov.io/github/jorgepiloto/pyturb/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/jorgepiloto/pyturb

.. |version| image:: https://img.shields.io/pypi/v/pyturb.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/pyturb

.. |commits-since| image:: https://img.shields.io/github/commits-since/jorgepiloto/pyturb/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/jorgepiloto/pyturb/compare/v0.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/pyturb.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/pyturb

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pyturb.svg
    :alt: Supported versions
    :target: https://pypi.org/project/pyturb

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pyturb.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/pyturb


.. end-badges

A Python package for aerospace propulsion computations

* Free software: MIT license

Installation
============

::

    pip install pyturb

Documentation
=============


https://pyturb.readthedocs.io/


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
