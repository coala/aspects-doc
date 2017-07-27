+----------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.ClassSize.ClassConstants`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------------------------------+--------------------------------------------+----------------------------------------------+
| **Sibling aspects** | `ClassInstanceVariables <../ClassInstanceVariables/README.rst>`_ | `ClassLength <../ClassLength/README.rst>`_ | `ClassMethods <../ClassMethods/README.rst>`_ |
+---------------------+------------------------------------------------------------------+--------------------------------------------+----------------------------------------------+

ClassConstants
==============
Number of constants in a class.

Tastes
========

+------------------+----------------------------------------------------+----------------------------------------------------+
| Taste            |  Meaning                                           |  Values                                            |
+==================+====================================================+====================================================+
|                  |                                                    |                                                    |
|``max_constants`` | Represents the max number of constants for a class | **3**                                              +
|                  |                                                    |                                                    |
+------------------+----------------------------------------------------+----------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Java

    // Here is an example of class with too many constants if we assume
    // that the maximum number of constants per class is 4
    
    class Aclass {
        final public int a = 1;
        final public int b = 2;
        final public String c = "coala";
        final public String d = "aspectsYEAH";
        final public Boolean e = true;
    
        public Aclass(){}
    }


Importance
==========

Avoids having too many constants to spare developers from the neeed
to remember too many of them.

How to fix this
==========

`ClassConstants` issues can be fixed by using data classes.

