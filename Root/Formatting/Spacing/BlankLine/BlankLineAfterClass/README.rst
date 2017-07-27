+-----------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing.BlankLine.BlankLineAfterClass`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-----------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------------------------------------+--------------------------------------------------------------------+----------------------------------------------+
| **Sibling aspects** | `BlankLineAfterDeclaration <../BlankLineAfterDeclaration/README.rst>`_ | `BlankLineAfterProcedure <../BlankLineAfterProcedure/README.rst>`_ | `NewlineAtEOF <../NewlineAtEOF/README.rst>`_ |
+---------------------+------------------------------------------------------------------------+--------------------------------------------------------------------+----------------------------------------------+

BlankLineAfterClass
===================
Those found after classes' definitions.

Tastes
========

+----------------------------+-----------------------------------------------------+-----------------------------------------------------+
| Taste                      |  Meaning                                            |  Values                                             |
+============================+=====================================================+=====================================================+
|                            |                                                     |                                                     |
|``blank_lines_after_class`` | Represents the number of blank lines to use after a | **2**, 1                                            |
|                            | classdefinition.                                    |                                                     |
|                            |                                                     |                                                     |
+----------------------------+-----------------------------------------------------+-----------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python 3

    class SomeClass:
        def __init__(self):
            raise RuntimeError('Never instantiate this class')
    
    
    def func():
        pass


Importance
==========

Having a specific number of blank lines after every classes'
definitions declarations improves on the readability of the code.

How to fix this
==========

        

