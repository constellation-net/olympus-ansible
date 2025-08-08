# Olympus Ansible Playbooks

This is a series of Ansible playbooks to configure all Olympus virtual machines.

## What this does

1. Installs the latest version of Docker
2. Add SSH public keys to the `authorized_keys` file
3. Disable SSH password authentication

## Running

```shell
pip install -r requirements.txt
ansible-playbook run.yml --ask-become-pass
```