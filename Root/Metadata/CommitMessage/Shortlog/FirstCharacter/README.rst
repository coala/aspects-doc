+---------------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Metadata.CommitMessage.Shortlog.FirstCharacter`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+---------------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+----------------------------------+--------------------------------+--------------------------------------------------+
| **Sibling aspects** | `ColonExistence <../ColonExistence/README.rst>`_ | `Length <../Length/README.rst>`_ | `Tense <../Tense/README.rst>`_ | `TrailingPeriod <../TrailingPeriod/README.rst>`_ |
+---------------------+--------------------------------------------------+----------------------------------+--------------------------------+--------------------------------------------------+

FirstCharacter
==============
The first character of your commit message shortlog (first line) usually
should be upper or lower case consistently.

If the commit message contains a colon, only the first character after
the colon will be checked.

Tastes
========

+-------------------------------+--------------------------------------------------------------+--------------------------------------------------------------+
| Taste                         |  Meaning                                                     |  Values                                                      |
+===============================+==============================================================+==============================================================+
|                               |                                                              |                                                              |
|``shortlog_starts_upper_case`` | Whether or not the shortlog (first line) of a commit         | **True**, False                                              |
|                               | message should start with an upper case letter consistently. |                                                              |
|                               |                                                              |                                                              |
+-------------------------------+--------------------------------------------------------------+--------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: English

    Add coverage pragma
    Compatability: Add coverage pragma
    add coverage pragma
    Compatability: add coverage pragma


Importance
==========

Consistent commit messages are easier to read through.

How to fix this
==========

Convert your first character to upper/lower case. If your message starts
with an identifier, consider rephrasing. Usually starting with a verb is
a good idea.

