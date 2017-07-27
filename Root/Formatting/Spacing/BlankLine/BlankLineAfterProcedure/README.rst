+---------------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing.BlankLine.BlankLineAfterProcedure`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------------------------+------------------------------------------------------------------------+----------------------------------------------+
| **Sibling aspects** | `BlankLineAfterClass <../BlankLineAfterClass/README.rst>`_ | `BlankLineAfterDeclaration <../BlankLineAfterDeclaration/README.rst>`_ | `NewlineAtEOF <../NewlineAtEOF/README.rst>`_ |
+---------------------+------------------------------------------------------------+------------------------------------------------------------------------+----------------------------------------------+

BlankLineAfterProcedure
=======================
Those found after procedures or functions.

Tastes
========

+---------------------------------+-----------------------------------------------------+-----------------------------------------------------+
| Taste                           |  Meaning                                            |  Values                                             |
+=================================+=====================================================+=====================================================+
|                                 |                                                     |                                                     |
|``blank_lines_after_procedures`` | Represents the number of blank lines to use after a | **1**, 0, 2                                         |
|                                 | procedure ora function                              |                                                     |
|                                 |                                                     |                                                     |
+---------------------------------+-----------------------------------------------------+-----------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: C

    #include <stdio.h>
    
    void proc(void){
        printf("this does nothing");
    } int add(float a, float b){
        return a + b;
    }


Importance
==========

Having a specific and reasonable number of blank lines after every
procedures improves on the readability of the code.

How to fix this
==========

`BlankLintAfterProcedure` issues can be fixed specifying (and of
course using) a reasonable number of blank lines to use after
procedures' definition.

