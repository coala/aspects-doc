+-------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.ClassSize.ClassLength`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+------------------------------------------------------------------+----------------------------------------------+
| **Sibling aspects** | `ClassConstants <../ClassConstants/README.rst>`_ | `ClassInstanceVariables <../ClassInstanceVariables/README.rst>`_ | `ClassMethods <../ClassMethods/README.rst>`_ |
+---------------------+--------------------------------------------------+------------------------------------------------------------------+----------------------------------------------+

ClassLength
===========
Number of lines of code in class' definition.

Tastes
========

+---------------------+--------------------------------------------------------------+--------------------------------------------------------------+
| Taste               |  Meaning                                                     |  Values                                                      |
+=====================+==============================================================+==============================================================+
|                     |                                                              |                                                              |
|``max_class_length`` | Represents the max number of lines for a class's definition. | **900**, 999                                                 +
|                     |                                                              |                                                              |
+---------------------+--------------------------------------------------------------+--------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python 3

    # Here is an example of a large class (in terms of number of lines) if
    # we assume that the maximum number of lines per class defintion is 10
    
    class Student:
        def __init__(self, first_name, last_name, dob,
                     matricule, school, faculty, department,
                     level, courses):
            self.first_name = first_name
            self.last_name = last_name
            self.dob = dob
            self.matricule = matricule
            self.school = school
            self.faculty = faculty
            self.department = department
            self.level = level
            self.courses = courses


Importance
==========

Too large classes are difficult to read and maintain, and can easily
introduce bugs or duplication in our code base.

How to fix this
==========

Usually splitting up those classes into other classes solves the
problem.

