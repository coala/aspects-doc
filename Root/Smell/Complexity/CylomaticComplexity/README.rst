+-----------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.Complexity.CylomaticComplexity`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-----------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------------------+
| **Sibling aspects** | `MaintainabilityIndex <../MaintainabilityIndex/README.rst>`_ |
+---------------------+--------------------------------------------------------------+

CylomaticComplexity
===================
Number of linearly independent paths through a program's source code.

The `Cyclomatic complexity
<https://wikipedia.org/wiki/Cyclomatic_complexity>`_  was developed by
Thomas J. McCabe in 1976 and it is based on a control flow representation
of the program.

Tastes
========

+--------------------------+----------------------------------------------------------+----------------------------------------------------------+
| Taste                    |  Meaning                                                 |  Values                                                  |
+==========================+==========================================================+==========================================================+
|                          |                                                          |                                                          |
|``cyclomatic_complexity`` | This the maximum number of embedded branches or embedded | **6**                                                    |
|                          | loops allowed.                                           |                                                          |
|                          |                                                          |                                                          |
+--------------------------+----------------------------------------------------------+----------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: C

    // The cyclomatic complexity of this program is 4.
    
    int foo (int a, int b) {
        if (a > 17 && b < 42 && a+b < 55) {
            return 1;
        }
        return 2;
    }


Importance
==========

Very complex code are difficult to read, debug and maintain.
It is always a good idea to keep things as simple as possible.

How to fix this
==========

This can be solved by breaking down complex functions into smaller
onces.

