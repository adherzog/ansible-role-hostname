hostname
========

Set the hostname.

Role Variables
--------------

 * hostname: '{{ inventory_hostname }}'

    Specifies the hostname to set on the server. Defaults to the inventory_hostname, specified in the inventory.

Example Playbook
----------------

    - hosts: servers
      roles:
         - hostname

License
-------

BSD

Author Information
------------------

Adam Herzog <adam@adamherzog.com>
