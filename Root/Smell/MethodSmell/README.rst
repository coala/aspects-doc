+----------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.MethodSmell`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+------------------------------------------+------------------------------------------+----------------------------------+
| **Sibling aspects** | `ClassSmell <../ClassSmell/README.rst>`_ | `Complexity <../Complexity/README.rst>`_ | `Naming <../Naming/README.rst>`_ |
+---------------------+------------------------------------------+------------------------------------------+----------------------------------+

MethodSmell
===========
This aspect detects `code smells` related to methods' and functions
definitions in your codebase.

Method-level code smells indicate poorly defined method and or
functions (too long method or functions, or functions with too many
parameters) in your source code.

Subaspects
==========

* `LongMethod <LongMethod/README.rst>`_
* `LongParameterList <LongParameterList/README.rst>`_
Example
=======

.. code-block:: python

    * Long method
    * Long paramater list
    etc...


Importance
==========

Make your functions and methods unambiguous, easy to read and debug
by reducing the number of parameters and length of your methods and
functions.

How to fix this
==========

A fix for this would simply consist of redefining the functions
(and or method), making them shorter and reducing the number of
parameters (maybe by creating more functions or using libraries).

