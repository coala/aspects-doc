+--------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.UnusedVariable.UnusedLocalVariable`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+--------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------------------+----------------------------------------------------+
| **Sibling aspects** | `UnusedGlobalVariable <../UnusedGlobalVariable/README.rst>`_ | `UnusedParameter <../UnusedParameter/README.rst>`_ |
+---------------------+--------------------------------------------------------------+----------------------------------------------------+

UnusedLocalVariable
===================
These are variable which are defined locally but never used.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    def func():
        for i in range (5):
            a = 0
            print ( ' coala ' )


Importance
==========

They make the code difficult to maintain.

How to fix this
==========

These can easily be removed without consequences.

