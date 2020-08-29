Nagios Plugins
=========

This role enables you to install the necessary plugins for nagios to monitor correctly on Ubuntu and RHEL.

Example Playbook
----------------

Playbook example for the role

    - hosts: masterserver, clientservers
      become: true
      roles:
         - nagios_plugins

License
-------

BSD