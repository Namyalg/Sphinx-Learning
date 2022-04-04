.. Firstrst documentation master file, created by
   sphinx-quickstart on Sun Apr  3 15:03:27 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Firstrst's documentation!
====================================

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Contents:
   
   test.rst
   link.rst

.. This line will not be rendered
Hey, im namya
How are you
It refers to the section itself, see :ref:`link-demo`.

::

   this is is a code block


.. code::

   #include<iostream>


.. note::
   This is for a note

.. danger::
   This should not be done at any cost 

.. attention::
   For your attention, please follow this 


.. image:: ./sample.jfif

.. _install-guide:

Installation Guide
==================

Step 1: Create and activate a virtual environment

Step 2: pip install it


This is a link to my medium account `link`_.

.. _link: https://namyalg.medium.com/

.. _link-demo:

Linking, inter and intra
++++++++++++++++++++++++

Go to the links page :doc:`link`

Go to the test page :doc:`test`

.. this is glossary here
.. glossary::

   environment
      A structure where information about all documents under the root is
      saved, and used for cross-referencing.  The environment is pickled
      after the parsing stage, so that successive runs only need to read
      and parse new and changed documents.

   source directory
      The directory which, including its subdirectories, contains all
      source files for one Sphinx project.
