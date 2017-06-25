+-----------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.MethodSmell.MethodLength`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-----------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------------------------+
| **Sibling aspects** | `ParameterListLength <../ParameterListLength/README.rst>`_ |
+---------------------+------------------------------------------------------------+

MethodLength
============
Number of lines of code in a function or method definition.

Depending on the value of `method_length_count_comment`,
comments are considered. The `rule of 30
<https://dzone.com/articles/rule-30-%E2%80%93-when-method-class-or>`_
suggests that the maximum number of lines for a method is 30. ``PMD``
defines a default value of 100 lines per method, `checkstlye`` 150 and
60 (when comments are not considered), ``rubocop`` 10.

Tastes
========

+--------------------------------+--------------------------------------------------------+--------------------------------------------------------+
| Taste                          |  Meaning                                               |  Values                                                |
+================================+========================================================+========================================================+
|                                |                                                        |                                                        |
|``max_method_length``           | Represents the max number of lines for a method or a   | **30**, 10, 50, 60, 100                                |
|                                | function'sdefinition.                                  |                                                        |
|                                |                                                        |                                                        |
+--------------------------------+--------------------------------------------------------+--------------------------------------------------------+
|                                |                                                        |                                                        |
|``method_length_count_comment`` | Allows when set to `True` to considered comments while | **60**, 30, 100, 150                                   |
|                                | calculatingmethods' length.                            |                                                        |
|                                |                                                        |                                                        |
+--------------------------------+--------------------------------------------------------+--------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python

    def _is_positive(num):
        if num > 0:
            return True
        else:
            return False
    
    # This function can be defined as follow:
    
    def is_positive(num):
        return num > 0


Importance
==========

It is really important is to stay DRY ("Don't Repeat Yourself") and
respect separation of concerns. Long methods are sometimes faster and
easier to write, and don't lead to maintenance problems. But most of
the time they are an easy way to detect that something *may* be wrong
in the code, and that special care is required while maintaining it.

How to fix this
==========

Refactoring methods into smaller more generic methods, making code more
compact by using inline and language specific syntax tricks,
implementing methods or functions to avoid redundant operation(s),
making use of methods provided in libraries rather than reimplementing
them.

