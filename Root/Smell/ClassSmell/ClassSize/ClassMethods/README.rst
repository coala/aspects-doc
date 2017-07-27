+--------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.ClassSize.ClassMethods`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+--------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+------------------------------------------------------------------+--------------------------------------------+
| **Sibling aspects** | `ClassConstants <../ClassConstants/README.rst>`_ | `ClassInstanceVariables <../ClassInstanceVariables/README.rst>`_ | `ClassLength <../ClassLength/README.rst>`_ |
+---------------------+--------------------------------------------------+------------------------------------------------------------------+--------------------------------------------+

ClassMethods
============
Number of class methods a class has.

Tastes
========

+----------------+--------------------------------------------------+--------------------------------------------------+
| Taste          |  Meaning                                         |  Values                                          |
+================+==================================================+==================================================+
|                |                                                  |                                                  |
|``max_methods`` | Represents the max number of methods for a class | **3**                                            +
|                |                                                  |                                                  |
+----------------+--------------------------------------------------+--------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python 3

    # Here is an example of a class with too many methods
    # Assuming that the maximum per class is 5.
    
    class AClass:
        def x(self): pass
        def y(self): pass
        def z(self): pass
        def p(self): pass
        def q(self): pass
        def r(self): pass


Importance
==========

Refactoring these classes spares developers from the need to remember
a large number of methods.

How to fix this
==========

Usually splitting up those classes into other classes solves the
problem.

