+-------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing.TrailingSpace`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------+--------------------------------------------------------------+
| **Sibling aspects** | `BlankLine <../BlankLine/README.rst>`_ | `SpacesAroundOperator <../SpacesAroundOperator/README.rst>`_ |
+---------------------+----------------------------------------+--------------------------------------------------------------+

TrailingSpace
=============
Unnecessary whitespace at end of a line.

Trailing space is all whitespace found after the last non-whitespace
character on the line until the newline. This includes tabs "\\t",
blank lines, blanks etc.

Tastes
========

+--------------------------+-------------------------------------------------------------+-------------------------------------------------------------+
| Taste                    |  Meaning                                                    |  Values                                                     |
+==========================+=============================================================+=============================================================+
|                          |                                                             |                                                             |
|``allow_trailing_spaces`` | Determines whether or not trailing spaces should be allowed | **False**, True                                             |
|                          | or not.                                                     |                                                             |
|                          |                                                             |                                                             |
+--------------------------+-------------------------------------------------------------+-------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python

    def func( a ):  
          pass      


Importance
==========

Trailing spaces make code less readable and maintainable.

How to fix this
==========

Removing the trailing spaces.

