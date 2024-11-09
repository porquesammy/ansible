# Ansible

Welcome to my Ansible repository! This repository is for storing Ansible playbooks and configurations that I use to learn and practice Ansible, as well as to automate and manage my home-lab setup.

## About

This repository is part of my journey to learning automation with Ansible. It is for storing various playbooks, roles, and tasks that I use to set up and manage a variety of services and infrastructure in my home-lab environment. The goal is to automate repetitive tasks, streamline my home-lab management, and deepen my understanding of Ansible.

## Home Lab Setup Overview

My home-lab setup consists of the following:

- Virtual machines (VMs) running on various hypervisors (e.g., Proxmox)
- Containers (LXC's and Docker)
- Network configurations (basic routing, firewall settings)
- Application services (web servers, databases, monitoring systems)
- Infrastructure as Code (IaC) and environment reproducibility

## Getting Started

### Prerequisites

Before you can run any of the playbooks in this repository, make sure you have the following installed:

- **Ansible**: Version 2.9 or higher
- **Python**: Ansible requires Python 3.6+ (and the `python3-apt` library for managing Debian-based systems)
- **SSH Access**: Ensure SSH access is available to all target machines
- **Other dependencies**: Depending on the playbook, you might need Docker, proxmox, or other tools installed on your system.

### Clone the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/porquesammy/ansible.git
cd ansible
