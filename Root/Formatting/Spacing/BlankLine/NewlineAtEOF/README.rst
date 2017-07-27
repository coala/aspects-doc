+----------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing.BlankLine.NewlineAtEOF`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------------------------+------------------------------------------------------------------------+--------------------------------------------------------------------+
| **Sibling aspects** | `BlankLineAfterClass <../BlankLineAfterClass/README.rst>`_ | `BlankLineAfterDeclaration <../BlankLineAfterDeclaration/README.rst>`_ | `BlankLineAfterProcedure <../BlankLineAfterProcedure/README.rst>`_ |
+---------------------+------------------------------------------------------------+------------------------------------------------------------------------+--------------------------------------------------------------------+

NewlineAtEOF
============
Newline character (usually '\\n', aka CR) found at the end of file.

Tastes
========

+-------------------+------------------------------------------------+------------------------------------------------+
| Taste             |  Meaning                                       |  Values                                        |
+===================+================================================+================================================+
|                   |                                                |                                                |
|``newline_at_EOF`` | If ``True``, enforce a newline at End Of File. | **True**, False                                +
|                   |                                                |                                                |
+-------------------+------------------------------------------------+------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python

    def do_nothing():
        pass


Importance
==========

A text file consists of a series of lines, each of which ends with a
newline character (\\n). A file that is not empty and does not end
with a newline is therefore not a text file.

It's not just bad style, it can lead to unexpected behavior, utilities
that are supposed to operate on text files may not cope well with files
that don't end with a newline.

How to fix this
==========

`NewlineAtEOF` issues can be fixed by simply adding a newline at the
end of the file.

