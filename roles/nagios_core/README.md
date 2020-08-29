Nagios Core
=========

This role enables you to install and configure Nagios Core on Ubuntu and RHEL

Example Playbook
----------------

Playbook example for the role

    - hosts: masterserver
      become: true
      roles:
         - nagios_core

License
-------

BSD