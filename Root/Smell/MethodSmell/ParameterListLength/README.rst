+------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.MethodSmell.ParameterListLength`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------------+
| **Sibling aspects** | `MethodLength <../MethodLength/README.rst>`_ |
+---------------------+----------------------------------------------+

ParameterListLength
===================
Number of parameter a function or method has.

In the book "Code Complete", ISBN 0735619670 it is suggested that the
maximum number of parameter per function or method is 7; ``rubocop``
suggests 5.

Tastes
========

+-------------------+-------------------------------------------------------------+-------------------------------------------------------------+
| Taste             |  Meaning                                                    |  Values                                                     |
+===================+=============================================================+=============================================================+
|                   |                                                             |                                                             |
|``max_parameters`` | Represents the max number of parameters for a function or a | **7**, 5                                                    |
|                   | method.                                                     |                                                             |
|                   |                                                             |                                                             |
+-------------------+-------------------------------------------------------------+-------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python

    def func(a, b, c, d, e, f, g, h, i, j, k):
        pass


Importance
==========

Methods that take too many parameters are difficult to read, maintain
and work with, and callers of those method often have an awkward time
assembling all of the data and the resulting code is usually not pretty.

How to fix this
==========

This can be fixed by:

Instead of passing a group of data received from an object as
parameters, pass the object itself to the method.
Sometimes you can merge several parameters into a single object etc.

