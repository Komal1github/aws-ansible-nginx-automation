# AWS EC2 + Ansible Nginx Automation

## Project Overview
This project automates the deployment of an Nginx web server on AWS EC2 using Ansible.

## Tools Used
- AWS EC2 (Ubuntu)
- Ansible
- Linux (Ubuntu)
- SSH

## Architecture
Laptop → EC2 (Controller) → EC2 (Target)

## Steps
1. Launch 2 EC2 instances
2. Configure SSH key access
3. Install Ansible on controller
4. Create inventory file
5. Run Ansible playbook
6. Deploy Nginx automatically

## Result
Web server successfully deployed and accessible via public IP.
