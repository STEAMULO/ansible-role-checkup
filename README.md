Ansible Checkup
===============

Run several checks against hosts list and write html report

Requirements
------------

Role Variables
--------------

If ansible hosts vars needs to be print in report.

    checkup_print_details: false


Dependencies
------------


Example Playbook
----------------

    - hosts: all
      vars:
        checkup_print_details: true
      roles:
        - { role: ansible-role-checkup }

License
-------


Author Information
------------------

STEAMULO - http://www.steamulo.com
