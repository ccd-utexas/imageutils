imageutils
==========

Image processing utilities for Astropy.

* Code: https://github.com/astropy/imageutils
* Docs: https://imageutils.readthedocs.org/en/latest/imageutils/index.html

The docs contain a
`What is this? <https://imageutils.readthedocs.org/en/latest/imageutils/index.html#what-is-this>`__
and a 
`Related Astropy packages <https://imageutils.readthedocs.org/en/latest/imageutils/index.html#related-astropy-packages>`__
section that explain the scope and purpose of this package.

Status reports for developers
-----------------------------

.. image:: https://travis-ci.org/astropy/imageutils.png?branch=master
    :target: https://travis-ci.org/astropy/imageutils
    :alt: Test Status

.. image:: https://coveralls.io/repos/astropy/imageutils/badge.png
    :target: https://coveralls.io/r/astropy/imageutils
    :alt: Code Coverage

.. image:: https://landscape.io/github/astropy/imageutils/master/landscape.png
    :target: https://landscape.io/github/astropy/imageutils/master
    :alt: Code Health

Note for ccd-utexas:
=========

**Purpose:** This fork is used to control the imageutils version in use for tsphot.
When imageutils is integrated with astropy, or when a stable version is released, delete this repository
and use astropy.image through the Anaconda Python distribution.

**To install:** Install and update anaconda. Then clone this repository ; ``$ cd /path/to/imageutils``;
``$ python setup.py install``

**Note:** Import will fail if present working directory is ``/path/to/imageutils``.

Code in this repository is subject to being overwritten by subsequent releases of imageutils.

To update ccd-utexas/imageutils from astropy/imageutils:

- Navigate to https://github.com/ccd-utexas/imageutils

- click "Compare"

- click "Edit"

- Set:

  - base fork: ccd-utexas/imageutils  base: master

  - head fork: astropy/imageutils  compare: master

- This will merge astropy/imageutils into ccd-utexas/imageutils
