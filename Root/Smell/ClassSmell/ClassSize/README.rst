+-------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.ClassSize`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------+--------------------------------------------+
| **Sibling aspects** | `DataClump <../DataClump/README.rst>`_ | `FeatureEnvy <../FeatureEnvy/README.rst>`_ |
+---------------------+----------------------------------------+--------------------------------------------+

ClassSize
=========
Class size refers to the size of a class.

A class's size is based on:

    * the number of fields it contains,
    * the number of methods,
    * and the number of lines of code.

Subaspects
==========

* `ClassConstants <ClassConstants/README.rst>`_
* `ClassInstanceVariables <ClassInstanceVariables/README.rst>`_
* `ClassLength <ClassLength/README.rst>`_
* `ClassMethods <ClassMethods/README.rst>`_
Example
=======

.. code-block:: Java

    // This is large class given that the `max_class_length` is 20
    
    public class Employee
    {
        private float salary;
        private float bonusPercentage;
        private EmployeeType employeeType;
        public Employee(float salary, float bonusPercentage,
                        EmployeeType employeeType)
        {
            this.salary = salary;
            this.bonusPercentage = bonusPercentage;
            this.employeeType = employeeType;
        }
        public float CalculateSalary()
        {
            switch (employeeType)
            {
                case EmployeeType.Worker:
                    return salary;
                case EmployeeType.Supervisor:
                    return salary + (bonusPercentage * 0.5F);
                case EmployeeType.Manager:
                    return salary + (bonusPercentage * 0.7F);
            }
            return 0.0F;
        }
    }


Importance
==========

Refactoring large classes spares developers from the need to remember
a large number of attributes and methods. Splitting these classes
avoids duplication, and makes the code shorter and easier to maintain.
Sometimes a Lazy Class (a class that does too little) is created in
order to delineate intentions for future development, In this case,
try to maintain a balance between clarity and simplicity in your code;
and they should be deleted if they serve no purpose.

How to fix this
==========

Usually splitting up large classes into other classes or giving in
line Class treatment to component that are near useless can solve this
problem.

