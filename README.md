rompe.pip
=========

This tiny role makes sure PIP is installed on CentOS.

Requirements
------------

So far this has been created for CentOS only.

Role Variables
--------------

n/a

Dependencies
------------

Needs geerlingguy.repo-epel to make sure the EPEL repository is available.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: rompe.pip, tags: "pip" }

License
-------

MIT

Author Information
------------------

Created in 2019 by Ulf Rompe
