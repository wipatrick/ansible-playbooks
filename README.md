## ansible-playbooks

# Requirements
* Ansible
* SSH connection (passwordless)

# Getting Started

* Test connection 

```
ansible -i inventory/hosts rpi-sensors -m ping
```

* Edit hosts file in inventory folder.

* Run 

```
ansible-playbook -i inventory/hosts playbook.yml
```
