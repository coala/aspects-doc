+--------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.LargeClass`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+--------------------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+----------------------------------------+--------------------------------------------+
| **Sibling aspects** | `DataClump <../DataClump/README.rst>`_ | `FeatureEnvy <../FeatureEnvy/README.rst>`_ |
+---------------------+----------------------------------------+--------------------------------------------+

LargeClass
==========
This aspect checks for large classes in your code base. A large class
is a class that contains many fields, methods or lines of code.

Tastes
========

+--------------------------+--------------------------------------------------------------+--------------------------------------------------------------+
| Taste                    |  Meaning                                                     |  Values                                                      |
+==========================+==============================================================+==============================================================+
|                          |                                                              |                                                              |
|``max_class_length``      | Represents the max number of lines for a class's definition. | **999**                                                      +
|                          |                                                              |                                                              |
+--------------------------+--------------------------------------------------------------+--------------------------------------------------------------+
|                          |                                                              |                                                              |
|``max_constants``         | Represents the max number of constants for a class           | **3**                                                        +
|                          |                                                              |                                                              |
+--------------------------+--------------------------------------------------------------+--------------------------------------------------------------+
|                          |                                                              |                                                              |
|``max_instance_variable`` | Represents the max number of instance variable for a class   | **3**                                                        +
|                          |                                                              |                                                              |
+--------------------------+--------------------------------------------------------------+--------------------------------------------------------------+
|                          |                                                              |                                                              |
|``max_methods``           | Represents the max number of method for a class              | **3**                                                        +
|                          |                                                              |                                                              |
+--------------------------+--------------------------------------------------------------+--------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

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

Refactoring these classes spares developers from the need to remember
a large number of attributes and methods. Splitting these classes
avoids duplication, and makes the code shorter and easier to maintain.

How to fix this
==========

Usually splitting up those classes into many other classes solves the
problem.

