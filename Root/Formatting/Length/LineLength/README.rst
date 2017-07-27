+---------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Length.LineLength`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------+
| **Sibling aspects** | `FileLength <../FileLength/README.rst>`_ |
+---------------------+------------------------------------------+

LineLength
==========
Number of characters found in a line of code.

Tastes
========

+--------------------+-----------------------------------------+-----------------------------------------+
| Taste              |  Meaning                                |  Values                                 |
+====================+=========================================+=========================================+
|                    |                                         |                                         |
|``max_line_length`` | Maximum number of character for a line. | **80**, 79, 100, 120, 160               +
|                    |                                         |                                         |
+--------------------+-----------------------------------------+-----------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: 

    print('The length of this line is 38')


Importance
==========

Too long lines make code very difficult to read and maintain.

How to fix this
==========

Splitting long lines of code into multiple shorter lines whenever
possible. Avoiding the usage of in-line language specific constructs
whenever they result in too long lines.

