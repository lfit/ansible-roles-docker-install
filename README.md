docker-install
==============

Install Docker.

Requirements
------------

None.

Role Variables
--------------

mtu: Configures the mtu to assign to the Docker port.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lfit.docker-install }

License
-------

MIT

Author Information
------------------

Linux Foundation Release Engineering
