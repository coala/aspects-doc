+--------------------------------------+----------------------------+------------------------------------------------------------------+
| ``Root.Metadata.CommitMessage.Body`` | `Parent <../README.rst>`_  | `Index <//github.com/coala/aspect-docs/blob/master/README.rst>`_ |
+--------------------------------------+----------------------------+------------------------------------------------------------------+


+---------------------+----------------------------------------+--------------------------------------+
| **Sibling aspects** | `Emptiness <../Emptiness/README.rst>`_ | `Shortlog <../Shortlog/README.rst>`_ |
+---------------------+----------------------------------------+--------------------------------------+

Body
====
Your commit body may contain an elaborate description of your commit.

Subaspects
==========

* `Existence <Existence/README.rst>`_
* `Length <Length/README.rst>`_
Example
=======

.. code-block:: English

    CI: Revert requests breakage workaround
    
    # This is the commit message body
    
    This reverts "CI: Workaround requests un-vendoring of chardet"
    commit 638bff9cd85bedb7e2e8c6184b41f547eca4f97c.
    
    The broken bear VintBear has been disabled.
    
    Related to https://github.com/coala/coala/issues/4277


Importance
==========

Sometimes the commit message shortlog do not give enough information
on the code, in that case it is a good idea to have give some more
information in the commit message body.

How to fix this
==========

Enforce detailed, clear and meaningful commit messages' bodies.

