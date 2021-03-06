.. _tinc__ref_upgrade_nodes:

Upgrade notes
=============

The upgrade notes only describe necessary changes that you might need to make
to your setup in order to use a new role release. Refer to the
:ref:`tinc__ref_changelog` for more details about what has changed.

.. _tinc__ref_upgrade_nodes_v0.3:

Upgrade from v0.2.X to v0.3.X
-----------------------------

All inventory variables have been renamed so you might need to update your
inventory.
This script can come in handy to do this:

.. literalinclude:: scripts/upgrade-from-v0.2.X-to-v0.3.X
   :language: shell

The script is bundled with this role under
:file:`docs/scripts/upgrade-from-v0.2.X-to-v0.3.X` and can be invoked from
their.
