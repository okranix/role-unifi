Unifi Network Appliance
=========

Deploy the Unifi network appliance as docker container using docker-compose.

Requirements
------------

Docker must already be installed.

Role Variables
--------------

| Name                         | Comment                                                   | Default value  |
|------------------------------|-----------------------------------------------------------|----------------|
| unifi_mongo_pass        | Password for the unifi mongodb user                         | ``      |
| unifi_data_dir | Directory where the unifi folder will be created. | `/data` |

Dependencies
------------

-

Example Playbook
----------------

  ---
  - name: Unifi network-application setup
    hosts: unifi-host
    roles:
      - role: role-unifi


License
-------

BSD
