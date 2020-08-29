Nagios NRPE
=========

This role enables you to install and configure NRPE on client machine that undergoes monitoring on Ubuntu and RHEl.

Example Playbook
----------------

Playbook example for the role

    - hosts: clientservers
      become: true
      roles:
         - nagios_nrpe

License
-------

BSD