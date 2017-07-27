+-------------------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Metadata.CommitMessage.Shortlog.Length`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+-------------------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+--------------------------------------------------+--------------------------------------------------+--------------------------------+--------------------------------------------------+
| **Sibling aspects** | `ColonExistence <../ColonExistence/README.rst>`_ | `FirstCharacter <../FirstCharacter/README.rst>`_ | `Tense <../Tense/README.rst>`_ | `TrailingPeriod <../TrailingPeriod/README.rst>`_ |
+---------------------+--------------------------------------------------+--------------------------------------------------+--------------------------------+--------------------------------------------------+

Length
======
The length of your commit message shortlog (first line).

Tastes
========

+------------------------+------------------------------------------------------------+------------------------------------------------------------+
| Taste                  |  Meaning                                                   |  Values                                                    |
+========================+============================================================+============================================================+
|                        |                                                            |                                                            |
|``max_shortlog_length`` | The maximal number of characters the shortlog may contain. | **72**, 50, 80                                             +
|                        |                                                            |                                                            |
+------------------------+------------------------------------------------------------+------------------------------------------------------------+


\* bold denotes default value

Subaspects
==========

This aspect does not have any sub aspects.

Example
=======

.. code-block:: English

    Some people just write very long commit messages. Too long. "
    Even full sentences. And more of them, too!


Importance
==========

A good commit message should be quick to read and concise. Also, git
and platforms like GitHub do cut away everything beyond 72, sometimes
even 50 characters making any longer message unreadable.

How to fix this
==========

Try to compress your message:

- Using imperative tense usually saves a character or two
- Omitting a trailing period saves another character
- Leave out unneeded words or details
- Use common abbreviations like w/, w/o or &.

