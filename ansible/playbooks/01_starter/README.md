# 01_simple_playbook
This repository contains a simple ansible playbook to understand the working of ansible.

## Prerequisites
Below prerequisites must be fulfilled for the successful execution of code.

### Software Requirement
Resources in this repository are meant for use with Ansible. Make sure to install the below softwares from official sources/repositories.

- [python3](https://www.python.org/downloads/) >= 3.9.2
- [pip3](https://pypi.org/project/pip/) >= 20.3.4
- [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) >= 2.15

Post installation, make sure to check the versions of above installed softwares using the below commands.

- python3 --version
- pip3 --version
- ansible --version

## Playbook Execution
To execute the ansible playbook, go to command prompt and switch to the playbook directory and then run the following commands:

-   [Optional] `ansible-playbook <playbook_name> --check` # to run the playbook in dry run mode
-   [Required] `ansible-playbook <playbook_name>`         # to run the playbook for implementation

## References
- https://docs.ansible.com/ansible/latest/network/getting_started/first_playbook.html

## License
This repository is under MIT License.

## Providing feedback
Open an issue in this GitHub repository.