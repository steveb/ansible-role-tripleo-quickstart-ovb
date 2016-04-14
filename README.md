Role Name
=========

ansible-role-tripleo-quickstart-ovb

Requirements
------------

This role requires python-openstackclient and python-heatclient>=1.0.0

Role Variables
--------------

Dependencies
------------

No other galaxy roles are leveraged.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-role-tripleo-quickstart-ovb }

License
-------

Apache2

Author Information
------------------

Steve Baker <sbaker@redhat.com>