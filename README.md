# Ansible Web Server Deployment with Nginx and firewalld

This Ansible project automates the installation and configuration of an Nginx web server and opens HTTP traffic (port 80) using `firewalld` on a CentOS machine.

## What It Does

- Installs and enables Nginx
- Starts and enables the `firewalld` service
- Opens port 80 and 443 to allow HTTP traffic
- Ensures services are enabled and persist on reboot

## Requirements

- Ansible 2.9+
- A CentOS target machine (tested on CentOS 7/8)
- SSH access to the target with appropriate privileges (preferably as a user with sudo access)
