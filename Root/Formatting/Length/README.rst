+----------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Formatting.Length`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------+------------------------------------+
| **Sibling aspects** | `Quotation <../Quotation/README.rst>`_ | `Spacing <../Spacing/README.rst>`_ |
+---------------------+----------------------------------------+------------------------------------+

Length
======
Hold sub-aspects for file and line length.

Subaspects
==========

* `FileLength <FileLength/README.rst>`_
* `LineLength <LineLength/README.rst>`_
Example
=======

.. code-block:: Python

    # We assume that the maximum number of characters per line is 10
    # and that the maximum number of lines per files is 3.
    
    def run(bear, file, filename, aspectlist):
        return bear.run(file, filename, aspectlist)


Importance
==========

Too long lines of code and too large files result in code difficult to
read, understand and maintain.

How to fix this
==========

Length issues can be fixed by writing shorter lines of code (splitting
long lines into multiple shorter lines); writing shorter files
(splitting files into modules, writing shorter methods and classes.).

