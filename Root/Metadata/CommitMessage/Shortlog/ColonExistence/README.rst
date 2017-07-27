+---------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Metadata.CommitMessage.Shortlog.ColonExistence`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+----------------------------------+--------------------------------+--------------------------------------------------+
| **Sibling aspects** | `FirstCharacter <../FirstCharacter/README.rst>`_ | `Length <../Length/README.rst>`_ | `Tense <../Tense/README.rst>`_ | `TrailingPeriod <../TrailingPeriod/README.rst>`_ |
+---------------------+--------------------------------------------------+----------------------------------+--------------------------------+--------------------------------------------------+

ColonExistence
==============
Some projects force to use colons in the commit message shortlog
(first line).

Tastes
========

+-------------------+-----------------------------------------------------+-----------------------------------------------------+
| Taste             |  Meaning                                            |  Values                                             |
+===================+=====================================================+=====================================================+
|                   |                                                     |                                                     |
|``shortlog_colon`` | Whether or not the shortlog has to contain a colon. | **True**, False                                     +
|                   |                                                     |                                                     |
+-------------------+-----------------------------------------------------+-----------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: English

    FIX: Describe change further
    context: Describe change further


Importance
==========

The colon can be a useful separator for a context (e.g. a filename) so
the commit message makes more sense to the reader or a classification
(e.g. FIX, ...) or others. Some projects prefer not using colons
specifically: consistency is key.

How to fix this
==========

Add or remove the colon according to the commit message guidelines.

