+------------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.ClassSize.ClassInstanceVariables`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+------------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+--------------------------------------------+----------------------------------------------+
| **Sibling aspects** | `ClassConstants <../ClassConstants/README.rst>`_ | `ClassLength <../ClassLength/README.rst>`_ | `ClassMethods <../ClassMethods/README.rst>`_ |
+---------------------+--------------------------------------------------+--------------------------------------------+----------------------------------------------+

ClassInstanceVariables
======================
Number of instance variables in a class.

Tastes
========

+---------------------------+-------------------------------------------------------------+-------------------------------------------------------------+
| Taste                     |  Meaning                                                    |  Values                                                     |
+===========================+=============================================================+=============================================================+
|                           |                                                             |                                                             |
|``max_instance_variables`` | Represents the max number of instance variables for a class | **3**                                                       +
|                           |                                                             |                                                             |
+---------------------------+-------------------------------------------------------------+-------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Python 3

    # Here is an example of a class with a large number of instance
    # variables if we assume that the maximun nubmer of instance variables
    # per class is 5.
    
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

Refactoring these classes spares developers from the need to remember
a large number of attributes.

How to fix this
==========

Usually splitting up those classes into other classes solves the
problem.

