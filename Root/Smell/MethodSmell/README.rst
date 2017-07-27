+----------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.MethodSmell`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------+------------------------------------------+----------------------------------+
| **Sibling aspects** | `ClassSmell <../ClassSmell/README.rst>`_ | `Complexity <../Complexity/README.rst>`_ | `Naming <../Naming/README.rst>`_ |
+---------------------+------------------------------------------+------------------------------------------+----------------------------------+

MethodSmell
===========
Code smells related to a method or function definition.

Method-level code smells indicate poorly defined method and or
functions (too long method or functions, or functions with too many
parameters) in your source code.

Subaspects
==========

* `MethodLength <MethodLength/README.rst>`_
* `ParameterListLength <ParameterListLength/README.rst>`_
Example
=======

.. code-block:: Python

    def do_nothing(var1, var2, var3, var4, var5, var6, var7):
        pass


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

