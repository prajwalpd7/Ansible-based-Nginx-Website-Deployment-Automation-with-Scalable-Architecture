# Ansible-based Nginx Website Deployment Automation

This repository contains Ansible playbooks and configuration files for automating the deployment of Nginx websites.

## Project Overview

The goal of this project is to simplify the deployment process of Nginx websites using Ansible. It provides a scalable architecture and automation scripts to install Nginx, start the Nginx service, and deploy static websites.

## Features

- Automation of Nginx installation and configuration
- Environment-based server grouping and variable configuration
- Integration with Ansible facts gathering for system information

## Architecture

The project follows a scalable architecture to manage different environments (dev, prod) and enables remote updating and managing of configurations. The architecture includes:

- Ansible inventory file for server configuration and grouping
- Playbooks for Nginx installation, service management, and website deployment

## Usage

To use this project, follow these steps:

1. Set up your inventory file (`hosts`) with the necessary server configurations.
2. Adjust the playbook (`nginx_playbook.yml`) according to your requirements.
3. Execute the playbook using the `ansible-playbook` command.
4. Monitor the output to ensure successful installation and deployment.

## Contributions

Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.

## Resources

Here are some helpful resources for learning more about Ansible:

- [Ansible Documentation](https://docs.ansible.com/)
- [Ansible Galaxy](https://galaxy.ansible.com/)
- [Ansible Tower Documentation](https://docs.ansible.com/ansible-tower/)
