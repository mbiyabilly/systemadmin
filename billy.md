https://github.com/mbiyabilly/systemadmin.git# System Administration Projects

This repository contains a collection of system administration projects and scripts.

## Table of Contents

* [Introduction](#introduction)
* [Projects](#projects)
* [Contributing](#contributing)

## Introduction

This repository serves as a central location for my system administration projects. It includes scripts, configurations, and documentation related to various tasks and automation efforts. These projects aim to improve efficiency, security, and reliability of systems I manage.

## Projects

Here's a list of the projects in this repository:

* **[Automated Server Backup Script](projects/backup-script/README.md)**: A script for automating server backups to a remote location.
    * Includes: Script, configuration files, and documentation.
    * Languages: Bash, Python (depending on the script).
* **[System Monitoring Dashboard](projects/monitoring-dashboard/README.md)**: Configuration files and scripts for setting up a system monitoring dashboard using tools like Grafana and Prometheus.
    * Includes: Docker Compose files, configuration files, and setup instructions.
    * Tools: Grafana, Prometheus, Node exporter.
* **[User Account Management Script](projects/user-management/README.md)**: Scripts for automating user account creation, modification, and deletion.
    * Includes: Bash or Python scripts, and documentation on usage.
    * Languages: Bash, Python.
* **[Security Hardening Scripts](projects/security-hardening/README.md)**: Scripts and configurations for hardening system security.
    * Includes: Scripts to apply security best practices, and documentation.
    * Tools: `iptables`, `ufw`, `fail2ban`.
* **[Log Analysis Tools](projects/log-analysis/README.md)**: scripts for parsing and analyzing system logs.
    * Includes: Python and bash scripts, and documentation on usage.
    * Tools: `grep`, `awk`, python scripts.
* **[Docker Container Deployment Scripts](projects/docker-deployments/README.md)**: Scripts and docker compose files for deploying applications in docker containers.
    * Includes: Docker compose files, deployment scripts, and documentation.
    * Tools: Docker, Docker Compose.
* **[Configuration Management with Ansible](projects/ansible-playbooks/README.md)**: Ansible playbooks for automating system configuration.
    * Includes: Ansible playbooks, roles, and inventory files.
    * Tools: Ansible.
* **[Proxmox VE VM Deployment Automation](projects/proxmox-vm-deploy/README.md)**: Scripts for automating the deployment of virtual machines on Proxmox VE.
    * Includes: Scripts, configuration files, and documentation.
    * Languages: Bash, Python.
* **[Network Traffic Analysis with Wireshark](projects/wireshark-analysis/README.md)**: Wireshark capture files and analysis reports for network traffic monitoring.
    * Includes: PCAP files, analysis reports, and documentation.
    * Tools: Wireshark.
* **[Dockerized Suricata Intrusion Detection System](projects/docker-suricata/README.md)**: Docker Compose files and Suricata rules for setting up an IDS.
    * Includes: Docker Compose files, Suricata rules, and setup instructions.
    * Tools: Docker, Suricata.
* **[Wazuh SIEM Deployment and Configuration](projects/wazuh-siem/README.md)**: Configuration files and scripts for deploying and configuring Wazuh.
    * Includes: Docker Compose files, Wazuh configuration files, and setup instructions.
    * Tools: Docker, Wazuh.
* **[Splunk Log Analysis Dashboard](projects/splunk-dashboard/README.md)**: Splunk dashboards and search queries for log analysis and security monitoring.
    * Includes: Splunk dashboard configurations, search queries, and documentation.
    * Tools: Splunk.
* **[Secure SSH Configuration and Automation](projects/secure-ssh/README.md)**: Scripts and configurations for hardening SSH security and automating SSH tasks.
    * Includes: SSH configuration files, scripts, and documentation.
    * Tools: SSH.
* **[Automated system backup with Proxmox and SSH](projects/proxmox-backup/README.md)**: Scripts to automate backups of VM's hosted in proxmox and transfer them via ssh.
    * Includes: Bash Scripts, documentation.
    * Tools: Proxmox, SSH.
* **[Dockerized application deployment and monitoring](projects/docker-app-monitoring/README.md)**: Deploy docker applications and monitor them with splunk.
    * Includes: Docker compose files, splunk configurations.
    * Tools: Docker, Splunk.
    
**Note:** Each project directory contains its own `README.md` file with detailed instructions and information.

## Contributing

If you have suggestions or improvements, feel free to submit a pull request or open an issue.

1.  Fork the repository.
2.  Create a new branch for your changes.
3.  Commit your changes.
4.  Push your branch to your forked repository.
5.  Submit a pull request.

Please ensure your code is well-documented and follows best practices.

## License

This project is licensed under the [MIT License](LICENSE).
