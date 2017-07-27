+---------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Smell.ClassSmell.FeatureEnvy`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------+----------------------------------------+
| **Sibling aspects** | `ClassSize <../ClassSize/README.rst>`_ | `DataClump <../DataClump/README.rst>`_ |
+---------------------+----------------------------------------+----------------------------------------+

FeatureEnvy
===========
Classes that excessively use methods of other classes.

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: Java

    public class Phone {
        private final String unformattedNumber;
        public Phone(String unformattedNumber) {
            this.unformattedNumber = unformattedNumber;
        }
        public String getAreaCode() {
            return unformattedNumber.substring(0,3);
        }
        public String getPrefix() {
            return unformattedNumber.substring(3,6);
        }
        public String getNumber() {
            return unformattedNumber.substring(6,10);
        }
    }
    public class Customer…
        private Phone mobilePhone;
        public String getMobilePhoneNumber() {
            return "(" +
                mobilePhone.getAreaCode() + ") " +
                mobilePhone.getPrefix() + "-" +
                mobilePhone.getNumber();
        }
    }


Importance
==========

This smell may occur after fields are moved to a data class; which
makes the code less readable, and difficult to debug.

How to fix this
==========

Move the operations on data to the newly defined class(given that
the fields of one class were moved to this class) as well.

