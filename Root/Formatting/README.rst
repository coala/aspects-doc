+---------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------+------------------------------------------+--------------------------------------+--------------------------------+--------------------------------------+
| **Sibling aspects** | `Metadata <../Metadata/README.rst>`_ | `Redundancy <../Redundancy/README.rst>`_ | `Security <../Security/README.rst>`_ | `Smell <../Smell/README.rst>`_ | `Spelling <../Spelling/README.rst>`_ |
+---------------------+--------------------------------------+------------------------------------------+--------------------------------------+--------------------------------+--------------------------------------+

Formatting
==========
The visual appearance of source code.

Subaspects
==========

* `Length <Length/README.rst>`_
* `Quotation <Quotation/README.rst>`_
* `Spacing <Spacing/README.rst>`_
Example
=======

.. code-block:: Python

    # Here is an example of Python code with lots of
    # formatting issues including: trailing spaces, missing spaces
    # around operators, strange and inconsistent indentation etc.
    
    z = 'hello'+'world'
         def f ( a):
            pass


Importance
==========

A coding style (the of rules or guidelines used when writing the
source code) can drastically affect the readability, and
maintainability of a program and might as well introduce bugs.

How to fix this
==========

Defining a clearly and thoughtful coding style (based on the available
ones given the programming language in use) and strictly respect it or
apply it through out the implementation of a project.

