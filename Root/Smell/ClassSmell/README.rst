+---------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------+--------------------------------------------+----------------------------------+
| **Sibling aspects** | `Complexity <../Complexity/README.rst>`_ | `MethodSmell <../MethodSmell/README.rst>`_ | `Naming <../Naming/README.rst>`_ |
+---------------------+------------------------------------------+--------------------------------------------+----------------------------------+

ClassSmell
==========
Code smells related to classes' definition.

Class-level code smells indicate poorly defined classes (including too
large classes or God object, data clump feature envy etc...) in your
source code.

Subaspects
==========

* `ClassSize <ClassSize/README.rst>`_
* `DataClump <DataClump/README.rst>`_
* `FeatureEnvy <FeatureEnvy/README.rst>`_
Example
=======

.. code-block:: Ruby

    class Warehouse
        def sale_price(item)
            item.price - item.rebate
        end
    end
    
    # sale_price refers to item more than self.


Importance
==========

These classes should be refactored for better readability and
maintainability of your source code.

How to fix this
==========

When a class is wearing too many (functional) hats (too large
classes), you should probably think about splitting it up:

* Extract class
* Extract subclass
* Extract interface

