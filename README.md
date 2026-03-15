# AWS Infrastructure Automation with Ansible & Python

This project demonstrates Infrastructure as Code (IaC) principles by automating the provisioning and configuration of a cloud environment.

## 🏗️ The Infrastructure


* **Provider:** AWS (EC2, VPC, Security Groups)
* **Configuration Management:** Ansible
* **Scripting:** Python (Boto3) & Bash
* **Services:** Docker, Nginx

## 📋 Features
- **Automated Provisioning:** Python script using Boto3 to launch EC2 instances.
- **Configuration:** Ansible playbooks to install Docker and Nginx.
- **Security:** Automated setup of Security Groups (Ports 22, 80, 443).
- **Deployment:** One-command setup for the entire environment.

## 🚀 Usage
1. **Provision:** Run the Python script to create the AWS resources.
   ```bash
   python3 provision_aws.py
