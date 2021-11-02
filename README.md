![GitHub](https://img.shields.io/github/license/d3athkai/MOTD-Login-Banner-for-Linux?style=plastic) ![GitHub](https://img.shields.io/badge/Python-2.7+-green?style=plastic) ![GitHub](https://img.shields.io/badge/Ansible-2.9+-blue?style=plastic) 

# Monit with Ansible
Deployment of Monit configuration and monitoring files using Ansible role.

## Monit
![Monit](https://mmonit.com/monit/img/logo.png)  
[Monit](https://mmonit.com/monit/) is a small Open Source utility for managing and monitoring Linux/Unix systems.  
Monit conducts automatic maintenance and repair and can execute meaningful causal actions in error situations.  
  
## Monit monitoring files
| S/N  | Monit  | Description  |
| ------------- | ------------- | ------------- |
| 1 | Root Filesystem | Monitor disk and inode utilization. |
| 2 | Network | Monitor upload and download speed and utilization. |
| 3 | SSL | Montior and alert when SSL certificate expiring soon. |
  
## Usage
1. Update hosts in `linux-monit.yml`  
2. Update variables in `roles/linux-monit/defaults/main.yml`  
3. Execute the playbook:<br>`ansible-playbook linux-monit.yml` 
  
