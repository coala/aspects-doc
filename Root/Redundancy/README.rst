+---------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------+--------------------------------------+--------------------------------------+--------------------------------+--------------------------------------+
| **Sibling aspects** | `Formatting <../Formatting/README.rst>`_ | `Metadata <../Metadata/README.rst>`_ | `Security <../Security/README.rst>`_ | `Smell <../Smell/README.rst>`_ | `Spelling <../Spelling/README.rst>`_ |
+---------------------+------------------------------------------+--------------------------------------+--------------------------------------+--------------------------------+--------------------------------------+

Redundancy
==========
This aspect describes redundancy in your source code.

Subaspects
==========

* `Clone <Clone/README.rst>`_
* `UnreachableCode <UnreachableCode/README.rst>`_
* `UnusedImport <UnusedImport/README.rst>`_
* `UnusedVariable <UnusedVariable/README.rst>`_
Example
=======

.. code-block:: C++

    int foo(int iX)
    {
        int iY = iX*2;
    
        return iX*2;
    }


Importance
==========

Redundant code makes your code harder to read and understand.

How to fix this
==========

Redundant code can usually be removed without consequences.

