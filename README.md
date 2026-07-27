# devopsIQ-prod

## Infrastructure Automation & Monitoring on GCP

This project demonstrates DevOps practices for automating infrastructure and monitoring on Google Cloud Platform.

### Tools Used
`GCP Compute Engine` | `Ansible` | `Nagios` | `Linux`

### What I Implemented
- **GCP Setup**: Launched VMs on GCP for Ansible Controller and Target Server
- **Ansible Automation**: Wrote playbooks to install Nginx and configure servers automatically
- **Nagios Monitoring**: Configured Nagios for server health monitoring - CPU, RAM, Disk

### How to Run
1. Clone this repo
2. Update inventory file with your GCP server IPs
3. Run: `ansible-playbook ansible-playbook.yml`

---
**Author**: Aayushi Shukla
