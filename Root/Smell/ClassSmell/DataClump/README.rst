+-------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.DataClump`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------+--------------------------------------------+
| **Sibling aspects** | `ClassSize <../ClassSize/README.rst>`_ | `FeatureEnvy <../FeatureEnvy/README.rst>`_ |
+---------------------+----------------------------------------+--------------------------------------------+

DataClump
=========
Identical groups of variables found in many different part of a program.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Java

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
            "Welcome %s %s, a %d-year-old %s from %s who works as a %s",
            firstName, lastName, age, gender, city, occupation
        );
    }


Importance
==========

Data clumps make code difficult to read, understand, and reuse.
It also spoils their architecture.

How to fix this
==========

Formally group the different variables together into a single object.

