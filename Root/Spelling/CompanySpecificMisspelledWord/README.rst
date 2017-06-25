+-------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Spelling.CompanySpecificMisspelledWord`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+----------------------------------------------------------------+
| **Sibling aspects** | `GeneralMisspelledWord <../GeneralMisspelledWord/README.rst>`_ |
+---------------------+----------------------------------------------------------------+

CompanySpecificMisspelledWord
=============================
This aspect checks for companies' or organisations' (like coala) specific
words' spelling.

Tastes
========

+------------------+-----------------------------------------------------+-----------------------------------------------------+
| Taste            |  Meaning                                            |  Values                                             |
+==================+=====================================================+=====================================================+
|                  |                                                     |                                                     |
|``specific_word`` | Represents the regex of the specific word to check. | ****                                                +
|                  |                                                     |                                                     |
+------------------+-----------------------------------------------------+-----------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: English

    `Coala`, `Aspects`, `aspectYEAH`.


Importance
==========

There are words you want to be written as you want, like your
organisation's name.

How to fix this
==========

Simply make sure those words match with what is provided by the
company.

