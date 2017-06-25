+------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.Complexity.MaintainabilityIndex`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------------------------+
| **Sibling aspects** | `CylomaticComplexity <../CylomaticComplexity/README.rst>`_ |
+---------------------+------------------------------------------------------------+

MaintainabilityIndex
====================
Software metric which measure how maintainable is a program.

The `maintainablity index
<www.projectcodemeter.com/cost_estimation/help/GL_maintainability.htm>`_
is always in the range 0-100 and is ranked
as follow:

* A `MI` in the range 0-9 maps to a code extremely difficult to maintain.
* A `MI` in the range 10-19 maps to a maintainable code.
* A `MI` in the range 20-100 maps to a code highly maintainable.

Tastes
========

+--------------------------+------------------------------------+------------------------------------+
| Taste                    |  Meaning                           |  Values                            |
+==========================+====================================+====================================+
|                          |                                    |                                    |
|``maintainability_index`` | Maintainability index of your code | **10**, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99+
|                          |                                    |                                    |
+--------------------------+------------------------------------+------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python

    '''
    The maintainability index for the following piece of code is 100.
    '''
    def preorder(node):
        if tree:
            print(node.key)
            preorder(node.left)
            preorder(node.right)


Importance
==========

Complex codes are difficult to maintain.

How to fix this
==========

This can be solved by writing simpler functions and methods.

