Network OSPF Configuration
=========

This role will configure ospf parameters for various network vendors (still in development)

Requirements
------------
ncclient


Role Variables
--------------
* router_id: router id
* ospf_areas:
  * id: area id
  * interfaces
    * name: interface name
    * type: p2p
    * passive: True|False

Dependencies
------------


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
