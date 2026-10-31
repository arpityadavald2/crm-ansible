# crm-ansible
Server configuration for the CRM project.

## Setup
Ansible runs from the dev server and connects to `crm-dev-target` over SSH
(private IP, key in `~/.ssh/crm-target`, never committed).

## Check the connection
    ansible all -m ping
