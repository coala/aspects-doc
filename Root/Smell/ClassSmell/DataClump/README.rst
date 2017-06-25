+-------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.DataClump`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------------+----------------------------+------------------------------------------------------------------+

+---------------------+--------------------------------------------+------------------------------------------+
| **Sibling aspects** | `FeatureEnvy <../FeatureEnvy/README.rst>`_ | `LargeClass <../LargeClass/README.rst>`_ |
+---------------------+--------------------------------------------+------------------------------------------+

DataClump
=========
This aspect detects `data clumps` in you codebase.

`Data clump` is a name given to any group of variables which are passed
around together (in a clump) throughout various parts of the program.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: java

            public static void main(String args[]) {
    
                String firstName = args[0];
                String lastName = args[1];
                Integer age = new Integer(args[2]);
                String gender = args[3];
                String occupation = args[4];
                String city = args[5];
    
                welcomeNew(firstName,lastName,age,gender,occupation,city);
            }
    
            public static void welcomeNew(String firstName, String lastName,
                                  Integer age, String gender,
                                  String occupation, String city){
    
                System.out.printf(
                    "Welcome %s %s, a %d-year-old %s from %s who works as a%s
    ",
                    firstName, lastName, age, gender, city, occupation
                );
            }
            


Importance
==========

Data clumps make codes difficult to read and understand, hardly
reusable, and less organized.

How to fix this
==========

Formally group the different variables together into a single object.

