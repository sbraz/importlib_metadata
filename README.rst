.. image:: https://img.shields.io/pypi/v/importlib_metadata.svg
   :target: `PyPI link`_

.. image:: https://img.shields.io/pypi/pyversions/importlib_metadata.svg
   :target: `PyPI link`_

.. _PyPI link: https://pypi.org/project/importlib_metadata

.. image:: https://github.com/python/importlib_metadata/workflows/Automated%20Tests/badge.svg
   :target: https://github.com/python/importlib_metadata/actions?query=workflow%3A%22Automated+Tests%22
   :alt: Automated Tests

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black
   :alt: Code style: Black

.. image:: https://readthedocs.org/projects/importlib-metadata/badge/?version=latest
   :target: https://importlib-metadata.readthedocs.io/en/latest/?badge=latest


``importlib_metadata`` is a library to access the metadata for a
Python package.

As of Python 3.8, this functionality has been added to the
`Python standard library
<https://docs.python.org/3/library/importlib.metadata.html>`_.
This package supplies backports of that functionality including
improvements added to subsequent Python versions.


Usage
=====

See the `online documentation <https://importlib_metadata.readthedocs.io/>`_
for usage details.

`Finder authors
<https://docs.python.org/3/reference/import.html#finders-and-loaders>`_ can
also add support for custom package installers.  See the above documentation
for details.


Caveats
=======

This project primarily supports third-party packages installed by PyPA
tools (or other conforming packages). It does not support:

- Packages in the stdlib.
- Packages installed without metadata.

Project details
===============

 * Project home: https://github.com/python/importlib_metadata
 * Report bugs at: https://github.com/python/importlib_metadata/issues
 * Code hosting: https://github.com/python/importlib_metadata
 * Documentation: https://importlib_metadata.readthedocs.io/
