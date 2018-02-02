========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |requires|
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-deploy-tool/badge/?style=flat
    :target: https://readthedocs.org/projects/python-deploy-tool
    :alt: Documentation Status

.. |requires| image:: https://requires.io/github/admjls/python-deploy-tool/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/admjls/python-deploy-tool/requirements/?branch=master

.. |version| image:: https://img.shields.io/pypi/v/deploy-tool.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/deploy-tool

.. |commits-since| image:: https://img.shields.io/github/commits-since/admjls/python-deploy-tool/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/admjls/python-deploy-tool/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/deploy-tool.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/deploy-tool

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/deploy-tool.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/deploy-tool

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/deploy-tool.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/deploy-tool


.. end-badges

Tool for deploying things from Anthill to AWS.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install deploy-tool

Documentation
=============

https://python-deploy-tool.readthedocs.io/

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
