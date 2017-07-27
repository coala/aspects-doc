+---------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.Complexity`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------+--------------------------------------------+----------------------------------+
| **Sibling aspects** | `ClassSmell <../ClassSmell/README.rst>`_ | `MethodSmell <../MethodSmell/README.rst>`_ | `Naming <../Naming/README.rst>`_ |
+---------------------+------------------------------------------+--------------------------------------------+----------------------------------+

Complexity
==========
Complexity of a code based on different complexity metrics.

Subaspects
==========

* `CylomaticComplexity <CylomaticComplexity/README.rst>`_
* `MaintainabilityIndex <MaintainabilityIndex/README.rst>`_
Example
=======

.. code-block:: reStructuredText

    * McCabe's complexity
    * Halstead complexity
    * Elshof complexity
    * Data complexity
    etc...
    
    Here is an example of complex code:
    https://github.com/sympy/sympy/blob/master/sympy/solvers/solvers.py


Importance
==========

Complex programs are difficult to read and maintain. Reducing a code's
complexity improves its organization.

How to fix this
==========

Implementing simple methods, avoiding too many branches, avoiding too
much multilevel inheritance etc... can fix this.

