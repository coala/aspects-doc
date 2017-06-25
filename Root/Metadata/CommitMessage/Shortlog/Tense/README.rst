+------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Metadata.CommitMessage.Shortlog.Tense`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+--------------------------------------------------+----------------------------------+--------------------------------------------------+
| **Sibling aspects** | `ColonExistence <../ColonExistence/README.rst>`_ | `FirstCharacter <../FirstCharacter/README.rst>`_ | `Length <../Length/README.rst>`_ | `TrailingPeriod <../TrailingPeriod/README.rst>`_ |
+---------------------+--------------------------------------------------+--------------------------------------------------+----------------------------------+--------------------------------------------------+

Tense
=====
Most projects have a convention on which tense to use in the commit
shortlog (the first line of the commit message).

Tastes
========

+-------------------+----------------------------+----------------------------+
| Taste             |  Meaning                   |  Values                    |
+===================+============================+============================+
|                   |                            |                            |
|``shortlog_tense`` | The tense of the shortlog. | **imperative**, present continuous, past+
|                   |                            |                            |
+-------------------+----------------------------+----------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: English

    Add file
    Adding file
    Added file


Importance
==========

Consistency is key to make messages more readable.

How to fix this
==========

Rephrase the shortlog into the right tense.

