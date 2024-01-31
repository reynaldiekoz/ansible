# Ansible Experimental

Welcome to Ansible Experimental! This repository contains Ansible playbooks for various tasks.

## Adding SSH Key

To add the SSH key, make sure you have the same PEM key on the target servers.

Run Command example:

```bash
ansible-playbook -i hosts install_docker.yaml
ansible-playbook add-key.yml -i hosts --key-file /home/ubuntu/ansible/key.pem
