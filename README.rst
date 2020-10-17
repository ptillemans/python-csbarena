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
        | |coveralls| |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-csbarena/badge/?style=flat
    :target: https://readthedocs.org/projects/python-csbarena
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/ptillemans/python-csbarena.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/ptillemans/python-csbarena

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/ptillemans/python-csbarena?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/ptillemans/python-csbarena

.. |requires| image:: https://requires.io/github/ptillemans/python-csbarena/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/ptillemans/python-csbarena/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/ptillemans/python-csbarena/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/ptillemans/python-csbarena

.. |codecov| image:: https://codecov.io/gh/ptillemans/python-csbarena/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/ptillemans/python-csbarena

.. |version| image:: https://img.shields.io/pypi/v/csbarena.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/csbarena

.. |wheel| image:: https://img.shields.io/pypi/wheel/csbarena.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/csbarena

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/csbarena.svg
    :alt: Supported versions
    :target: https://pypi.org/project/csbarena

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/csbarena.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/csbarena

.. |commits-since| image:: https://img.shields.io/github/commits-since/ptillemans/python-csbarena/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/ptillemans/python-csbarena/compare/v0.1.0...master



.. end-badges

Arena for Codingame Coders Strike Back

* Free software: GNU Lesser General Public License v3 or later (LGPLv3+)

Installation
============

::

    pip install csbarena

You can also install the in-development version with::

    pip install https://github.com/ptillemans/python-csbarena/archive/master.zip


Documentation
=============


https://python-csbarena.readthedocs.io/


Development
===========

To run all the tests run::

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
