Network OSPF Configuration
=========

This role will configure ospf parameters for various network vendors (still in development)

Requirements
------------


Role Variables
--------------


Dependencies
------------

ncclient

Example Playbook
----------------

    - hosts: vmx1
      roles:
         - { role: network_ospf_configuration }

License
-------

BSD

Author Information
------------------

Marc Colburn
