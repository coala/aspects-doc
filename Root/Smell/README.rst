+----------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+----------------+----------------------------+------------------------------------------------------------------+


+---------------------+------------------------------------------+--------------------------------------+------------------------------------------+--------------------------------------+--------------------------------------+
| **Sibling aspects** | `Formatting <../Formatting/README.rst>`_ | `Metadata <../Metadata/README.rst>`_ | `Redundancy <../Redundancy/README.rst>`_ | `Security <../Security/README.rst>`_ | `Spelling <../Spelling/README.rst>`_ |
+---------------------+------------------------------------------+--------------------------------------+------------------------------------------+--------------------------------------+--------------------------------------+

Smell
=====
Symptom in a piece of code that possibly indicates a deeper problem.

`Smells` are certain structures in a code that indicate violation of
fundamental design principles. They are usually not bugs; they are not
technically incorrect and do not currently prevent the program from
functioning.

Subaspects
==========

* `ClassSmell <ClassSmell/README.rst>`_
* `Complexity <Complexity/README.rst>`_
* `MethodSmell <MethodSmell/README.rst>`_
* `Naming <Naming/README.rst>`_
Example
=======

.. code-block:: Ruby

    =begin
    Example of Ruby code with data clumps and methods with too many
    parameters.
    =end
    class Dummy
        def x(y1, y2, y3, y4, y5, y6, y7, y8, a); end
        def y(y1, y2, y3, y4, y5, y6, y7, y8); end
        def z(y1, y2, y3, y4, y5, y6, y7, y8); end
    end


Importance
==========

Even though they are not necessarily bugs, code smells increase the
risk of bugs or failure in the future and may slow down development.

How to fix this
==========

There are several `refactoring techniques` that can be used to deal
with `code smells` including:

* Composing methods
* Moving features between objects
* Organizing data
* Simplifying conditional expressions
* Simplifying method calls
* Dealing with generalisation

See <https://sourcemaking.com/refactoring/refactorings> for more
information.

