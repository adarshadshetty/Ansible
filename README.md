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

> Dynamic Inventory for EC2
> Execute Ansible Playbook with terraform
> Ansible and Docker
> Ansible and K8s
> Ansible and Jenkins
> Roles in Ansible 

> Project : Deploy Nodejs App
> Project : Deploy Nexus


