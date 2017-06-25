+---------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing.BlankLine`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------------------+------------------------------------------------+
| **Sibling aspects** | `SpacesAroundOperator <../SpacesAroundOperator/README.rst>`_ | `TrailingSpace <../TrailingSpace/README.rst>`_ |
+---------------------+--------------------------------------------------------------+------------------------------------------------+

BlankLine
=========
A line with zero characters.

Subaspects
==========

* `BlankLineAfterClass <BlankLineAfterClass/README.rst>`_
* `BlankLineAfterDeclaration <BlankLineAfterDeclaration/README.rst>`_
* `BlankLineAfterProcedure <BlankLineAfterProcedure/README.rst>`_
* `NewlineAtEOF <NewlineAtEOF/README.rst>`_
Example
=======

.. code-block:: Python 3

    name = input('What is your name?')
    
    
    print('Hi, {}'.format(name))


Importance
==========

Various programming styles use blank lines in different places.
The usage of blank lines affects the readability, maintainability and
length of a code i.e blank lines can either make code longer, less
readable and maintainable or do the reverse.

How to fix this
==========

Following specific rules about the usage of blank lines: using them
only when necessary.

