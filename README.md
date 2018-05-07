# ansible_workshop

#########################

This repo deploys a workshop environment: 
- creates users 
- creates groups
- updates and installs packages. 
- Pushes configuration files and modules. 

#########################

INSTRUCTIONS for DEPLOYING USER ENVIRONMENT:

1. Clone this repo!

2. Edit "vars.yml" to define users and groups

3. Edit "main.yml" with an IP Address of your target host 

3. To deploy, in the working directory, run "ansible-playbook main.yml"

(Ansible is required on the host executing the playbook. The correct modules must be present on the host in /root/modules)

#############

** Currently need to define passwords for users as the root user via the terminal. Needs passwords defined in playbook ** 
