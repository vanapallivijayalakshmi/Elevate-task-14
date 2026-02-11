# Task 14 – Configuration Management using Ansible

This task demonstrates basic Ansible configuration management by:
- Installing Nginx on localhost
- Starting and enabling Nginx service
- Verifying using curl http://localhost

## Files
- inventory.ini
- playbook.yml

## How to Run
ansible-playbook -i inventory.ini playbook.yml -K

## Output
Nginx welcome page is shown on http://localhost
