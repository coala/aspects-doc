+---------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Length.FileLength`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------+
| **Sibling aspects** | `LineLength <../LineLength/README.rst>`_ |
+---------------------+------------------------------------------+

FileLength
==========
Number of lines found in a file.

Tastes
========

+--------------------+-----------------------------------+-----------------------------------+
| Taste              |  Meaning                          |  Values                           |
+====================+===================================+===================================+
|                    |                                   |                                   |
|``max_file_length`` | Maximum number of line for a file | **999**                           +
|                    |                                   |                                   |
+--------------------+-----------------------------------+-----------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python 3

    # This file would be a large file if we assume that the max number of
    # lines per file is 10
    
    class Node:
        def __init__(self, value, left_most_child, left_sibling):
            self.value=value
            self.left_most_child=left_most_child
            self.left_sibling=left_sibling
    
    # This is example is just showing what this aspect is about, because
    # the max number of lines per file is usually 999.


Importance
==========

Too long programs (or files) are difficult to read, maintain and
understand.

How to fix this
==========

Splitting files into modules, writing shorter methods and classes.

