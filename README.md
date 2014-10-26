Introduction
======

Ansible role to install the supervisord process manager to control the services. It aims to be as generic as possible so does not use any distro specific package managers. It uses pip to install and assumes that python is already present on the machine which is a fair assumption if its running ansible.

To install the role:

ansible-galaxy install -p <your_roles> sgargan.supervisor

TODO:
=======
Determine distro and install correct script from here:

https://github.com/Supervisor/initscripts
