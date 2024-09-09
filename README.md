# ansible-playbook-install-vagrant
Ansible playbook to automate the installation of Vagrant on Linux. It handles dependencies and installs the latest version from the official repository for easy VM management.

BEFORE INSTALLATION
maybe you need check folder permission
add
```
[local]
localhost ansible_connection=local
```
in Ansible host

1. open terminal from Ansible folder
2. run git clone https://github.com/dad1755/ansible-playbook-install-vagrant.git
3. run ansible-playbook install_vagrant.yml -v
