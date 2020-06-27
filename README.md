# NagiosWithAnsible
Installation and Configuration of Nagios Core, NRPE and Nagios Plugins on RHEL EC2

# Prepare inventory
Create inventory list of master server and client machine under the respective groups

# Execution
```
ansible-playbook -i inventory.txt playbook
```
# On AWS
If your're running this role AWS make sure that security group allows port 5666
