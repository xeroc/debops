.. Copyright (C) 2016-2017 Robin Schneider <ypid@riseup.net>
.. Copyright (C) 2016-2017 DebOps <https://debops.org/>
.. SPDX-License-Identifier: GPL-3.0-or-later

.. _apt_cacher_ng__ref_upgrade_nodes:

Upgrade notes
=============

The upgrade notes only describe necessary changes that you might need to make
to your setup in order to use a new role release. Refer to the
changelog for more details about what has changed.

.. _apt_cacher_ng__ref_upgrade_nodes_v0.2.0:

Upgrade from v0.1.0 to v0.2.0
-----------------------------

A few variables have been renamed so you might need to update your inventory.
This script can come in handy to do this:

.. literalinclude:: scripts/upgrade-from-v0.1.X-to-v0.2.X
   :language: shell
   :lines: 1,6-

The script is bundled with this role under
:file:`./docs/scripts/upgrade-from-v0.1.X-to-v0.2.X` and can be invoked from
their.
