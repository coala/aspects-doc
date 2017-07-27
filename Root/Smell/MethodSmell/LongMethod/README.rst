+---------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.MethodSmell.LongMethod`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+--------------------------------------------------------+
| **Sibling aspects** | `LongParameterList <../LongParameterList/README.rst>`_ |
+---------------------+--------------------------------------------------------+

LongMethod
==========
This aspect checks for methods and functions with a large number
of lines.

Tastes
========

+----------------------+------------------------------------------------------+------------------------------------------------------+
| Taste                |  Meaning                                             |  Values                                              |
+======================+======================================================+======================================================+
|                      |                                                      |                                                      |
|``max_method_length`` | Represents the max number of lines for a method or a | **40**, 5                                            |
|                      | function'sdefinition.                                |                                                      |
|                      |                                                      |                                                      |
+----------------------+------------------------------------------------------+------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: python

    # Here is a method with one line of code
    def func():
        print('coala is always written with lowercase `c`.')


Importance
==========

The longer a method or function is, the harder it becomes to
understand and maintain it. Also long methods easily introduce
unwanted duplicated code, and bugs to our codebase.

How to fix this
==========

Extracting methods or functions is a fix for this.

