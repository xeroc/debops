.. Copyright (C) 2014-2018 Maciej Delmanowski <drybjed@gmail.com>
.. Copyright (C) 2014-2018 DebOps <https://debops.org/>
.. SPDX-License-Identifier: GPL-3.0-or-later

Getting started
===============

By default ``debops.dhcpd`` installs a DHCP server with some default
configuration. Server will not be authoritative, and will have a default subnet
configuration taken from ``ansible_default_ipv4`` network configuration.

An example playbook which uses ``debops.dhcpd`` role::

    ---

    - name: Manage DHCP server
      hosts: debops_dhcpd

      roles:
        - role: debops.dhcpd
          tags: dhcpd

