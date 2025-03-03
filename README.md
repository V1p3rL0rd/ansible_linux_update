# Ansible linux update and apply security patches
This is a very simple Ansible playbook will help you to update your linux hosts and apply security patches.

The playbook contains several tasks:

1) Update the apt package index
2) Upgrade all packages to the latest version
3) Install unattended-upgrades package
4) Enable unattended upgrades
5) Configure unattended-upgrades for security updates
