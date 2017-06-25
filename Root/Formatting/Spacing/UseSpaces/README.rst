+---------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing.UseSpaces`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+----------------------------------------+--------------------------------------------------------------+------------------------------------------------+
| **Sibling aspects** | `BlankLine <../BlankLine/README.rst>`_ | `SpacesAroundOperator <../SpacesAroundOperator/README.rst>`_ | `TrailingSpace <../TrailingSpace/README.rst>`_ |
+---------------------+----------------------------------------+--------------------------------------------------------------+------------------------------------------------+

UseSpaces
=========
Determines if spaces should be used over tabs.
    

Tastes
========

+----------------+---------------------------------------------------------+---------------------------------------------------------+
| Taste          |  Meaning                                                |  Values                                                 |
+================+=========================================================+=========================================================+
|                |                                                         |                                                         |
|``indent_size`` | Represents the number of space per indentation level.   | **4**, 8                                                +
|                |                                                         |                                                         |
+----------------+---------------------------------------------------------+---------------------------------------------------------+
|                |                                                         |                                                         |
|``use_spaces``  | Determines whether spaces should be use for indentation | **True**, False                                         +
|                |                                                         |                                                         |
+----------------+---------------------------------------------------------+---------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    def func(a, b):
        result = a**b
    \treturn result


Importance
==========

A tab could be a different number of columns depending on the
environment(text editor), but a space is always one column. For
readability and portability purposes, it is important to use either
of them consistently.

How to fix this
==========

Use either spaces or tabs for indentation not both. In case you are
using spaces, specified the number of space to be use per indentation
level.

