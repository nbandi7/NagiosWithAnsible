# NagiosWithAnsible
Installation and Configuration of Nagios Core, NRPE and Nagios Plugins on RHEL and Ubuntu

# Prerequisites
Ansible Controller Machine which have ssh trust between the servers it is communnicating.

# Prepare inventory
Create inventory list of master server and client machine under the respective groups. 

# Execution
```
ansible-playbook -i inventory.txt playbook.yml
```
# On AWS
If your're running this role on AWS make sure that **Security group** allows port **5666**
