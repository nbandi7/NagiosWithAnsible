# NagiosWithAnsible
Installation and Configuration of Nagios Core, NRPE and Nagios Plugins on RHEL and Ubuntu

# Prerequisites
Install Ansible on the respective os.

# Prepare inventory
Create inventory list of master server and client machine under the respective groups

# Execution
```
ansible-playbook -i inventory.txt playbook
```
# On AWS
If your're running this role on AWS make sure that security group allows port 5666
