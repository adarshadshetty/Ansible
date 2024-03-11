# Ansible
This is Ansible Repo

Day 3:
Ansible Command


Insttalling Ansible

sudo apt update
sudo apt install ansible

create inventory file --> vim inventory [To store the the IP Address of the server] 

nano inventory  ctrl o , enter , ctrl x

ansible all --key-file ~/.ssh/ansible -i inventory -m ping
