# AnsibleHelloWorld
// POC project via ansible playbook


### Install 
```bash
# https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#from-pip

# (Mac osx : install ansible global)
# sudo python get-pip.py (optional)
sudo pip install ansible
```

### Quick start
```bash
# list all hosts
ansible all --list-hosts

# ping all servers 
ansible all -m ping
```