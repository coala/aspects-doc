+---------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.UnusedVariable.UnusedGlobalVariable`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------------------------+----------------------------------------------------+
| **Sibling aspects** | `UnusedLocalVariable <../UnusedLocalVariable/README.rst>`_ | `UnusedParameter <../UnusedParameter/README.rst>`_ |
+---------------------+------------------------------------------------------------+----------------------------------------------------+

UnusedGlobalVariable
====================
These are variable which have a global scope but are never used.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    a = 0
    for i in range (5):
        print ( ' coala ' )


Importance
==========

They make the code difficult to maintain.

How to fix this
==========

These can easily be removed without consequences.

