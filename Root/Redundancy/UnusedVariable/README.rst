+------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.UnusedVariable`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------+----------------------------------------------------+----------------------------------------------+
| **Sibling aspects** | `Clone <../Clone/README.rst>`_ | `UnreachableCode <../UnreachableCode/README.rst>`_ | `UnusedImport <../UnusedImport/README.rst>`_ |
+---------------------+--------------------------------+----------------------------------------------------+----------------------------------------------+

UnusedVariable
==============
Unused variables are declared but never used.

Subaspects
==========

* `UnusedGlobalVariable <UnusedGlobalVariable/README.rst>`_
* `UnusedLocalVariable <UnusedLocalVariable/README.rst>`_
* `UnusedParameter <UnusedParameter/README.rst>`_
Example
=======

.. code-block:: python

    a = {}
    print ('coala')


Importance
==========

Unused variables can degrade performance marginally but more importantly
makes the source code harder to read and understand.

How to fix this
==========

Those variables can easily be removed without consequences.

