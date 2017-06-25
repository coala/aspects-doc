+----------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.UnusedVariable.UnusedParameter`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------------------+------------------------------------------------------------+
| **Sibling aspects** | `UnusedGlobalVariable <../UnusedGlobalVariable/README.rst>`_ | `UnusedLocalVariable <../UnusedLocalVariable/README.rst>`_ |
+---------------------+--------------------------------------------------------------+------------------------------------------------------------+

UnusedParameter
===============
Unused parameters are functions arguments which are never used.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    def func(a):
        pass


Importance
==========

Unused paramaters are useless to functions, they them difficult to
use and maintain.

How to fix this
==========

Those parameters can easily be removed without consequences.

