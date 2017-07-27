+-----------------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing.BlankLine.BlankLineAfterDeclaration`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-----------------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------------------------+--------------------------------------------------------------------+----------------------------------------------+
| **Sibling aspects** | `BlankLineAfterClass <../BlankLineAfterClass/README.rst>`_ | `BlankLineAfterProcedure <../BlankLineAfterProcedure/README.rst>`_ | `NewlineAtEOF <../NewlineAtEOF/README.rst>`_ |
+---------------------+------------------------------------------------------------+--------------------------------------------------------------------+----------------------------------------------+

BlankLineAfterDeclaration
=========================
Those found after declarations.

Tastes
========

+-----------------------------------+---------------------------------------------------------+---------------------------------------------------------+
| Taste                             |  Meaning                                                |  Values                                                 |
+===================================+=========================================================+=========================================================+
|                                   |                                                         |                                                         |
|``blank_lines_after_declarations`` | Represents the number of blank lines after declarations | **0**, 1, 2                                             +
|                                   |                                                         |                                                         |
+-----------------------------------+---------------------------------------------------------+---------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: C

    #include <stdio.h>
    
    int main ()
    {
      int a;
      float b;
    
      scanf("%d%f", &a, &b);
      printf("a = %d and b = %f", a, b);
      return 0;
    }


Importance
==========

Having a specific and reasonable number of blank lines after every
block of declarations improves on the readability of the code.

How to fix this
==========

`BlankLintAfterDeclaration` issues can be fixed specifying (and of
course using) a reasonable number of blank lines to use after block
declaration.

