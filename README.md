DEEPaaS
=========

Ansible role to deploy DEEP as a Service (DEEPaaS) on Linux.

Requirements
------------

The role uses Python pip to install DEEPaaS. In RedHat systems ..

Role Variables
--------------

Currently just `prerequisites` variable is required, which lists the packages 
needed for DEEPaaS installation (see default value in `defaults/main.yml`).

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: indigo-dc.deepaas }

License
-------

Apache License 2.0
