# Ansible Box
This repository contains various items related to Ansible.

## WSL
WSL contains docker and samba roles. To install docker in your wsl distro, execute commands as follows in the wsl terminal.
```bash
sudo apt update
sudo apt install ansible-core

git clone https://github.com/aconitum3/AnsibleBox
cd AnsibleBox/WSL
ansible-playbook Playbook.yml
```
To reflect the addition of the docker group, you must log in again.