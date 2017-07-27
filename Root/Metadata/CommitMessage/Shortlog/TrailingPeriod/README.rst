+---------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Metadata.CommitMessage.Shortlog.TrailingPeriod`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+--------------------------------------------------+----------------------------------+--------------------------------+
| **Sibling aspects** | `ColonExistence <../ColonExistence/README.rst>`_ | `FirstCharacter <../FirstCharacter/README.rst>`_ | `Length <../Length/README.rst>`_ | `Tense <../Tense/README.rst>`_ |
+---------------------+--------------------------------------------------+--------------------------------------------------+----------------------------------+--------------------------------+

TrailingPeriod
==============
Some projects force not to use trailing periods in the commit
message shortlog (first line).

Tastes
========

+--------------------+-------------------------------------------------------+-------------------------------------------------------+
| Taste              |  Meaning                                              |  Values                                               |
+====================+=======================================================+=======================================================+
|                    |                                                       |                                                       |
|``shortlog_period`` | Whether or not the shortlog has to contain a trailing | **False**, True                                       |
|                    | period.                                               |                                                       |
|                    |                                                       |                                                       |
+--------------------+-------------------------------------------------------+-------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: English

    Describe change.
    Describe change


Importance
==========

Consistency is key to make messages more readable. Removing a trailing
period can also make the message shorter by a character.

How to fix this
==========

Add or remove the trailing period according to the commit message
guidelines.

