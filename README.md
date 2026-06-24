🚀 Lab Overview
This repository contains production-ready Ansible playbooks designed to replace manual sysadmin workflows with scalable automation.

The primary playbook (automate_grp_user.yml) automates user provisioning and secure environment setup:

Idempotency: Ensures predictable, repeatable system states across multiple execution runs.

User Management: Provisions multiple system users utilizing loops and forces secure password expiration on first login.

Directory Security: Creates collaborative workspaces (/shares/devops_project) with strict 0770 permissions and group ownership allocations.
