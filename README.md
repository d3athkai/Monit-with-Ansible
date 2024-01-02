[![GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-BE0000?style=plastic)](#)  
[![Rocky Linux](https://img.shields.io/badge/RockyLinux-07BA82?style=plastic)](#) [![Ubuntu+](https://img.shields.io/badge/Ubuntu-DD4814?style=plastic)](#) [![Raspberry Pi OS](https://img.shields.io/badge/Raspberry--Pi--OS-C51A4A?style=plastic)](#)  
[![Ansible](https://img.shields.io/badge/Ansible-131211?style=plastic)](#) [![Python 3](https://img.shields.io/badge/Python-3-3673A5?style=plastic)](#)  

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
