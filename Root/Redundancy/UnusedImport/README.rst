+----------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.UnusedImport`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------+----------------------------------------------------+--------------------------------------------------+
| **Sibling aspects** | `Clone <../Clone/README.rst>`_ | `UnreachableCode <../UnreachableCode/README.rst>`_ | `UnusedVariable <../UnusedVariable/README.rst>`_ |
+---------------------+--------------------------------+----------------------------------------------------+--------------------------------------------------+

UnusedImport
============
Unused imports are any kind of import/include that is not needed.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    import sys
    import os
    
    print('coala is always written with lowercase c')


Importance
==========

Redundant imports can cause a performance degrade and make code
harder to understand when reading through it. Also it causes
unneeded dependencies within your modules. In most programming
languages, unused imports may have side effects and that may
be a common false positive. However those should be avoided.

How to fix this
==========

Usually, unused imports can simply be removed.

