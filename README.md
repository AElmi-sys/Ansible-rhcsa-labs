# Linux Systems & Ansible Automation Labs

Hands-on RHEL/Ansible lab portfolio focused on Linux system administration, configuration management, security, storage, services, and automation.

## What this repository demonstrates

- **Ansible fundamentals:** playbooks, inventories, variables, loops, conditionals, handlers, blocks/rescue/always
- **Linux administration:** users and groups, packages, services, system information, storage and LVM
- **Security:** SELinux and firewalld configuration
- **Configuration management:** Jinja2 templates and reusable variables
- **Infrastructure automation:** web-server and repository configuration
- **Troubleshooting mindset:** validation tasks and repeatable administrative workflows

## Lab areas

| Area | Examples |
|---|---|
| Users & groups | User creation, group management, shared directories |
| Storage | LVM, filesystems, mounts, storage setup |
| Services | Service management, validation, handlers |
| Security | SELinux, firewalld |
| Packages | Conditional and standard package installation |
| Templates | Jinja2-driven configuration |
| System administration | Host information and system reports |
| Ansible control | Variables, loops, conditions, blocks and handlers |

## Repository structure

The playbooks are being organized by administration topic so the repository can be used both as a study record and as a professional portfolio.

```text
playbooks/
├── users-groups/
├── storage/
├── security/
├── services/
├── packages/
├── webserver/
└── system/

templates/
vars/
inventory/
docs/
```

> Some existing lab files are intentionally retained while this repository is being cleaned and reorganized. Local shell history, editor state, swap files, credentials, and real environment-specific inventory data should not be committed.

## Technologies

- RHEL / Rocky Linux
- Ansible
- YAML
- Jinja2
- SELinux
- firewalld
- systemd
- LVM
- Git / GitHub

## Purpose

This repository documents hands-on preparation for Linux system administration and the Red Hat Ansible/RHCE skill set. The goal is to demonstrate practical automation rather than only theoretical knowledge.

**Author:** AElmi-sys
