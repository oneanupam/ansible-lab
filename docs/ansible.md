# 📘 Ansible Commands Reference
This repository contains a curated list of essential `Ansible` commands for running and managing Ansbile playbooks and roles efficiently. Useful for daily reference and quick lookups.

# Ansible Basics
Ansible is an open source software that automates software provisioning, configuration management, and application deployment. Ansible and it's modules are written in Python. After installation, you will find a directory "/etc/ansible". Inside this directory, two files are present -
1. `ansible.cfg` The settings in Ansible are adjustable via a configuration file.
2. `hosts` Ansible works against multiple systems in our infrastructure at the same time. It does this by selecting portions of systems listed in Ansible inventory.

By default, Ansible uses OpenSSH for remote communication and has a default inventory file where you can define which servers will be managed. The default inventory file is: /etc/ansible/hosts

Below are some key terms/concetps -
1. `Playbook` These are the files written in YAML format that instruct Ansible on what to do. Playbooks are written in YAML format. Files can be of any name but their content must be written in YAML format and saved it as ".yml" or ".yaml" extension.
2. `Modules` It perform configuration and system management. Ansible modules are written in python language. Ansible ships with number of modules that can be executed directly on remote hosts through playbooks.
---

## 🧱 Useful Commands

```bash
# 1. Config Management
ansible --version # Check the installed ansible core version
ansible-doc -l # To list the modules present in the ansible:

# 2. Playbook Execution
ansible-playbook <playbook_name> # To run a ansible playbook
ansible-playbook system.yml --syntax-check # To check the syntaz, if syntax is OK, it will return the playbook name
ansible-playbook system.yml --check # To run a playbook in dry run mode (also called Check Mode). It wont make any changes.
```

## 📌 How to Contribute
Feel free to fork this repo and add your favorite ansible commands!

## References
- https://docs.ansible.com/projects/ansible/latest/command_guide/cheatsheet.html
- https://docs.ansible.com/projects/ansible/latest/cli/ansible-playbook.html#ansible-playbook
