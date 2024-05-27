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
1. Ansible 
2. Ad-Hoc Commands 
3. Task Plays & Playbook 
4. Ansible Config File 
5. Server Configuration 
6. Configuration Applications 
7. Working with File 
8. Working with common Modules
9. Ansible Collections & Galaxy
10. Ansible Playbook
11. Troubleshooting
12. Privilege Escalation
13.Conditionals , and more!


### Advanced Topics & Integration with other Technologies

1. Dynamic Inventory for EC2 
2. Execute Ansible Playbook with terraform 
3. Ansible and Docker 
4. Ansible and K8s 
5. Ansible and Jenkins 
6. Roles in Ansible 

> Project : Deploy Nodejs App \
> Project : Deploy Nexus \


