+----------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.MethodSmell.LongParameterList`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+------------------------------------------+
| **Sibling aspects** | `LongMethod <../LongMethod/README.rst>`_ |
+---------------------+------------------------------------------+

LongParameterList
=================
This aspect checks for methods and functions with a large number of
parameters.

Tastes
========

+-------------------+-------------------------------------------------------------+-------------------------------------------------------------+
| Taste             |  Meaning                                                    |  Values                                                     |
+===================+=============================================================+=============================================================+
|                   |                                                             |                                                             |
|``max_parameters`` | Represents the max number of parameters for a function or a | **10**, 5                                                   |
|                   | method.                                                     |                                                             |
|                   |                                                             |                                                             |
+-------------------+-------------------------------------------------------------+-------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    def func(a, b, c, d, e, f, g, h, i, j, k):
        pass


Importance
==========

Refactoring such methods and functions may reveal some duplicated
code, make the code shorter, easy to read and maintain.

How to fix this
==========

This can be fixed by:

Instead of passing a group of data received from an object as
parameters, pass the object itself to the method.
Sometimes you can several merge parameters into a single parameter
object etc.

