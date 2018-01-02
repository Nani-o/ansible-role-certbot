certbot
=======

A role I use for installing certbot. It relies on an nginx in order to validate certs using the webroot option of certbot.

Compatibility
-------------

  - CentOS 7

Requirements
------------

You need to setup nginx. 
This role automatically include a role named nginx at start, you can use whatever role to create the webroot, I use the one by [geerlingguy](https://github.com/geerlingguy/ansible-role-nginx).

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
