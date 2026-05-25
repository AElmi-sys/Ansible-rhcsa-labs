
HEAD
# Ansible RHCSA Labs

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
