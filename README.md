# Ansible linux update and apply security patches
This simple Ansible playbook updates your linux hosts and apply security patches.
The script is executed in several stages:

1) Update the apt package index
2) Upgrade all packages to the latest version
3) Install unattended-upgrades package
4) Enable unattended upgrades
5) Configure unattended-upgrades for security updates
