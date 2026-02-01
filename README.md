# Ansible Local Apache Project

## Overview
This project demonstrates how to use **Ansible locally** to automate the installation, configuration, and cleanup of an **Apache web server** using Ansible best practices.

The same machine acts as:
- Ansible Control Node
- Managed Node (localhost)

---

## Project Structure

ansible-local-project/
├── inventory
├── playbook.yml
├── vars.yml
├── cleanup.yml
└── roles/
    └── webserver/
        ├── tasks/main.yml
        ├── handlers/main.yml
        └── templates/index.html.j2

