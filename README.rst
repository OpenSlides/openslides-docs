==========================
 OpenSlides documentation
==========================

Overview
========

This documentation repository contains the **outdated** OpenSlides manual of
OpenSlides 1.5.

**Note**: The (outdated) images (placed in "_images") are not added to this repository to
not inscrease the repo size. For rework of manual the images have to updated.
All old images can be found here in
`OpenSlides Core repo <https://github.com/OpenSlides/OpenSlides/tree/2.0b1/docs/_images>`_.

Requirements
============

- sphinx
- sphinx-bootstrap-theme
see `requirements.txt`_

.. _requirements.txt: requirements.txt

How to build the documentation?
===============================

Instruction to build the docs on GNU/Linux.

Install setup::

    $ virtualenv .venv
    $ source .venv/bin/activate
    $ pip install -r requirements.txt

Build html output (created in _build/html)::

    $ make html

Build pdf output (created in _build/latex)::

    $ make latex
    $ make latexpdf


License and authors
===================

The documentation is licensed under
`Creative Commons CC BY-SA 3.0 <http://creativecommons.org/licenses/by-sa/3.0/>`_,
see LICENSE file. The authors are mentioned in the AUTHORS file.
