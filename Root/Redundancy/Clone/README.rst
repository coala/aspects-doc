+---------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Redundancy.Clone`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------------------+----------------------------------------------+--------------------------------------------------+
| **Sibling aspects** | `UnreachableCode <../UnreachableCode/README.rst>`_ | `UnusedImport <../UnusedImport/README.rst>`_ | `UnusedVariable <../UnusedVariable/README.rst>`_ |
+---------------------+----------------------------------------------------+----------------------------------------------+--------------------------------------------------+

Clone
=====
Code clones are multiple pieces of source code in your
codebase that are very similar.

Tastes
========

+---------------------+---------------------------------------------------------+---------------------------------------------------------+
| Taste               |  Meaning                                                |  Values                                                 |
+=====================+=========================================================+=========================================================+
|                     |                                                         |                                                         |
|``ignore_using``     | Ignore ``using`` directives in C#.                      | **False**, True                                         +
|                     |                                                         |                                                         |
+---------------------+---------------------------------------------------------+---------------------------------------------------------+
|                     |                                                         |                                                         |
|``min_clone_tokens`` | The number of tokens that have to be equal for it to be | **20**                                                  |
|                     | detected as a code clone.                               |                                                         |
|                     |                                                         |                                                         |
+---------------------+---------------------------------------------------------+---------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: C++

    extern int array_a[];
    extern int array_b[];
    
    int sum_a = 0;
    
    for (int i = 0; i < 4; i++)
        sum_a += array_a[i];
    
    int average_a = sum_a / 4;
    
    int sum_b = 0;
    
    for (int i = 0; i < 4; i++)
        sum_b += array_b[i];
    
    int average_b = sum_b / 4;


Importance
==========

Code clones make editing more difficult due to unnecessary increases
in complexity and length.

How to fix this
==========

Usually code clones can be simplified to only one occurrence. In a
lot of cases, both just use different values or variables and can
be reduced to one function called with different parameters or
loops.

