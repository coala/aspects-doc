+----------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.UnreachableCode.UnusedFunction`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------------------+
| **Sibling aspects** | `UnreachableStatement <../UnreachableStatement/README.rst>`_ |
+---------------------+--------------------------------------------------------------+

UnusedFunction
==============
An unused function is a function that is never called during
code execution.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    def func():
        pass
    
    print('coala is always written with lowercase c')


Importance
==========

Unused functions make the source code more longer and more
difficult to maintain.

How to fix this
==========

It is recommended to remove those functions. If you would like
to access it's source code later for other purposes, you can
rely on a version control system like Git, Mercurial or
Subversion.

