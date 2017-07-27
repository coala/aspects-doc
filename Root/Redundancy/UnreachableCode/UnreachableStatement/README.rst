+----------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.UnreachableCode.UnreachableStatement`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+
| **Sibling aspects** | `UnusedFunction <../UnusedFunction/README.rst>`_ |
+---------------------+--------------------------------------------------+

UnreachableStatement
====================
An unreachable statement is a statement that is never executed
during code execution.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    def func():
        return True
    
    if func():
        a = {}
    else:
        a = (i for i in range (5))
        print (id(a))


Importance
==========

We should always keep our codebase clean, having dead code uselessly
makes the code longer and ambiguous.

How to fix this
==========

These statement can be remove without harming the code.

