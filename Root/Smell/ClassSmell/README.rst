+---------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+------------------------------------------+--------------------------------------------+----------------------------------+
| **Sibling aspects** | `Complexity <../Complexity/README.rst>`_ | `MethodSmell <../MethodSmell/README.rst>`_ | `Naming <../Naming/README.rst>`_ |
+---------------------+------------------------------------------+--------------------------------------------+----------------------------------+

ClassSmell
==========
This aspect detects `code smells` or `bad smells` related to classes'
definitions in your codebase.

Class-level code smells indicate poorly defined classes (including too
large classes or God object, data clump feature envy etc...) in your
source code.

Subaspects
==========

* `DataClump <DataClump/README.rst>`_
* `FeatureEnvy <FeatureEnvy/README.rst>`_
* `LargeClass <LargeClass/README.rst>`_
Example
=======

.. code-block:: English

    * Too large classes
    * Data clump
    * Feature envy
    etc ...


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

