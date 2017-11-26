[![Build Status](https://travis-ci.org/Nani-o/ansible-role-jackett.svg?branch=master)](https://travis-ci.org/Nani-o/ansible-role-jackett)

jackett
=======

A role for installing [jackett](https://github.com/Jackett/Jackett) a proxy server that provides an API for torrent trackers.

Compatibility
-------------

  - CentOS 7
  - Ubuntu 14.04
  - Ubuntu 16.04
  - Debian 8
  - Debian 9

Requirements
------------

You need my mono [role](https://github.com/Nani-o/ansible-role-mono) or to install mono by yourself on the target host. The role will also install systemd along with a .service file for jackett.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jackett }

License
-------

MIT

Author Information
------------------

Sofiane MEDJKOUNE
