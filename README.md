# Ansible Automation Projects
This repository contains a collection of Ansible automation projects demonstrating infrastructure configuration, application deployment, containerization, Kubernetes orchestration, and AWS automation.
Each branch focuses on a specific DevOps use case and showcases how Ansible can be used to automate deployment workflows and infrastructure management.

## Branch Overview
### feature/deploy-nodejs
- Automates deployment of a Node.js application on a Linux server.
### feature/deploy-docker
- Automates Docker installation and container deployment.
### feature/deploy-to-k8s
- Automates deployment of applications to Kubernetes clusters.
### feature/dynamic-inventory-for-ec2
- Demonstrates dynamic inventory management using AWS EC2.
### feature/deploy-nexus
- Automates installation and configuration of Nexus Repository Manager.

### Install Ansible:
```python
sudo apt update
sudo apt install ansible -y
```
### Verify installation:
```python
ansible --version
```

## Getting Started
1. Clone the repository:
```python
git clone https://github.com/FPurichaya/ansible-project.git
cd ansible-project
```
2. Switch to the desired branch::
```python
git checkout feature/deploy-nodejs
```
3. Run a playbook:
```python
ansible-playbook -i deploy-node.yaml
```





