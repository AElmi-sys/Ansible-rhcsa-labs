 HEAD

HEAD
# Ansible RHCE Labs

A collection of Ansible playbooks designed to automate system administration, security hardening, and environment deployment for Red Hat Enterprise Linux (RHEL) environments.

## Featured Playbooks

*   **[Secure Web Deployment](secure_web.yml):** Automates the installation and hardening of web services, including firewalld and SELinux configurations.
*   **[User & Group Automation](automate_grp.yml):** Manages local user accounts, group assignments, and permissions at scale.
*   **[Environment Collaboration](collaborate_env.yml):** Sets up shared directories and collaborative team environments with proper permissions.

## How to Use This Repo
1. Clone the repository: `git clone git@github.com:AElmi-sys/Ansible-rhcsa-labs.git`
2. Update the `inventory` file with your target nodes.
3. Run a playbook: `ansible-playbook -i inventory secure_web.yml`
 2b12cfa (Update README.me)

🚀 Lab Overview
This repository contains production-ready Ansible playbooks designed to replace manual sysadmin workflows with scalable automation.

The primary playbook (automate_grp_user.yml) automates user provisioning and secure environment setup:

Idempotency: Ensures predictable, repeatable system states across multiple execution runs.

User Management: Provisions multiple system users utilizing loops and forces secure password expiration on first login.

Directory Security: Creates collaborative workspaces (/shares/devops_project) with strict 0770 permissions and group ownership allocations. 18bc54fb8209696f6c99997515b014e207ee0468
