+-----------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Spacing`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-----------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------+----------------------------------------+
| **Sibling aspects** | `Length <../Length/README.rst>`_ | `Quotation <../Quotation/README.rst>`_ |
+---------------------+----------------------------------+----------------------------------------+

Spacing
=======
All whitespace found between non-whitespace characters.

Subaspects
==========

* `BlankLine <BlankLine/README.rst>`_
* `SpacesAroundOperator <SpacesAroundOperator/README.rst>`_
* `TrailingSpace <TrailingSpace/README.rst>`_
Example
=======

.. code-block:: Python

    # Here is an example of code with spacing issues including
    # unnecessary blank lines and missing space around operators.
    
    
    
    def func(   ):
       return      37*-+2


Importance
==========

Useless spacing affects the readability and maintainability of a code.

How to fix this
==========

Removing the trailing spaces and the meaningless blank lines.

