certbot
=======

A role I use for installing certbot. It relies on an nginx in order to validate certs using the webroot option of certbot.

Compatibility
-------------

  - CentOS 7

Requirements
------------

You need to setup nginx.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: certbot }

License
-------

MIT

Author Information
------------------

Sofiane MEDJKOUNE
