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



### -------------------------------------------------------
### Core Concept
> Ansible , 
> Ad-Hoc Commands ,
> Task Plays & Playbook , 
> Ansible Config File , 
> Server Configuration , 
> Configuration Applications , 
> Working with File , 
> Working with common Modules , 
> Ansible Collections & Galaxy ,
> Ansible Playbook , 
> Troubleshooting , 
> Privilege Escalation , 
> Conditionals , and more!

### Advanced Topics & Integration with other Technologies

1. Dynamic Inventory for EC2 \
2. Execute Ansible Playbook with terraform \
3. Ansible and Docker \
4. Ansible and K8s \
5. Ansible and Jenkins \
6. Roles in Ansible 

> Project : Deploy Nodejs App \
> Project : Deploy Nexus \


