ansible-stack-django
====================

Ansible stack for deploying django application along with setting up nginx, postgresql etc.

To use this deployment script

- Edit env_vars/base.yml and give git url of your django application as well as project and application name
- Then edit vagrantfile accordingly
- Now run vagrant up --provision
