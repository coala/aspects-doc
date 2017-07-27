+-------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.UnreachableCode`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------+----------------------------------------------+--------------------------------------------------+
| **Sibling aspects** | `Clone <../Clone/README.rst>`_ | `UnusedImport <../UnusedImport/README.rst>`_ | `UnusedVariable <../UnusedVariable/README.rst>`_ |
+---------------------+--------------------------------+----------------------------------------------+--------------------------------------------------+

UnreachableCode
===============
Unreachable code, sometimes called dead code, is source code that
can never be executed during the program execution.

Subaspects
==========

* `UnreachableStatement <UnreachableStatement/README.rst>`_
* `UnusedFunction <UnusedFunction/README.rst>`_
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

Unreachable code, makes the source code longer and more difficult
to maintain.

How to fix this
==========

Those pieces of code can easily be removed without consequences.

