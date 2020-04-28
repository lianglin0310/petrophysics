========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/petrophysics/badge/?style=flat
    :target: https://readthedocs.org/projects/petrophysics
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/lianglin0310/petrophysics.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/lianglin0310/petrophysics

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/lianglin0310/petrophysics?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/lianglin0310/petrophysics

.. |requires| image:: https://requires.io/github/lianglin0310/petrophysics/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/lianglin0310/petrophysics/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/lianglin0310/petrophysics/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/lianglin0310/petrophysics

.. |version| image:: https://img.shields.io/pypi/v/petrophysics.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/petrophysics

.. |wheel| image:: https://img.shields.io/pypi/wheel/petrophysics.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/petrophysics

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/petrophysics.svg
    :alt: Supported versions
    :target: https://pypi.org/project/petrophysics

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/petrophysics.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/petrophysics

.. |commits-since| image:: https://img.shields.io/github/commits-since/lianglin0310/petrophysics/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/lianglin0310/petrophysics/compare/v0.0.0...master



.. end-badges

A Python package for petrophysics

* Free software: MIT license

Installation
============

::

    pip install petrophysics

You can also install the in-development version with::

    pip install https://github.com/lianglin0310/petrophysics/archive/master.zip


Documentation
=============


https://petrophysics.readthedocs.io/


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
