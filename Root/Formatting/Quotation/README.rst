+-------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Quotation`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------+------------------------------------+
| **Sibling aspects** | `Length <../Length/README.rst>`_ | `Spacing <../Spacing/README.rst>`_ |
+---------------------+----------------------------------+------------------------------------+

Quotation
=========
Quotation mark used for strings and docstrings.

Tastes
========

+------------------------+------------------------------------+------------------------------------+
| Taste                  |  Meaning                           |  Values                            |
+========================+====================================+====================================+
|                        |                                    |                                    |
|``preferred_quotation`` | Represents the preferred quotation | **'**, "                           +
|                        |                                    |                                    |
+------------------------+------------------------------------+------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python

    # Here is an example of code where both '' and "" quotation mark
    # Are used.
    
    string = 'coala is always written with lowercase c.'
    string = "coala is always written with lowercase c."


Importance
==========

Using the same quotation whenever possible in the code, improve on its
readability by introducing consistency.

How to fix this
==========

Choosing a preferred quotation and using it everywhere (if possible).

