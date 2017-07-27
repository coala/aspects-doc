+--------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing.SpacesAroundOperator`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+--------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------+------------------------------------------------+
| **Sibling aspects** | `BlankLine <../BlankLine/README.rst>`_ | `TrailingSpace <../TrailingSpace/README.rst>`_ |
+---------------------+----------------------------------------+------------------------------------------------+

SpacesAroundOperator
====================
Spacing around operators.

Tastes
========

+----------------------------+-------------------------------------------------------------+-------------------------------------------------------------+
| Taste                      |  Meaning                                                    |  Values                                                     |
+============================+=============================================================+=============================================================+
|                            |                                                             |                                                             |
|``spaces_after_colon``      | Represents the number of blank spaces after colons.         | **1**, 0                                                    +
|                            |                                                             |                                                             |
+----------------------------+-------------------------------------------------------------+-------------------------------------------------------------+
|                            |                                                             |                                                             |
|``spaces_around_operators`` | Represents the number of space to be used around operators. | **1**, 0                                                    +
|                            |                                                             |                                                             |
+----------------------------+-------------------------------------------------------------+-------------------------------------------------------------+
|                            |                                                             |                                                             |
|``spaces_before_colon``     | Represents the number of blank spaces before colons.        | **0**, 1                                                    +
|                            |                                                             |                                                             |
+----------------------------+-------------------------------------------------------------+-------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python

    def f(a, x):
        return 37+a[42 -  x]


Importance
==========

Having a specific and reasonable number of whitespace (blank) around
operators improves on the readability of the code.

How to fix this
==========

`SpacesAroundOperator` issues can be fixed by simply specifying and
the number of whitespace to be used after each operator.

