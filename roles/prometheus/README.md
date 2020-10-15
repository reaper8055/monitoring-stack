Role Name
=========

Ansible playbook to install docker-ce and docker compose in Ubuntu Server 20.04

Requirements
------------

Any system running this playbook should have ansible installed. Check [ansible installation docs](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) for platform specific instructions.

Role Variables
--------------

All role specific variables that can be changed are in defaults/main.yml

Run the Playbook
----------------

Have all your hosts in a [host-file](https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html).

ansible-playbook -i hosts grafana.yml -kK

License
-------

BSD
